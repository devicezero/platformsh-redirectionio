Update: Meanwhile, redirection.io is providing a repo directly, see https://github.com/redirectionio/platformsh-template for the latest version (the one you are looking at right now is just a PoC, it's not maintained)

This is a PoC to use redirection.io agent on Platform.sh, acting as a reverse proxy

To make this work you need

- a project key from redirection.io and create a environment variable in Platform.sh called `env:REDIRECTIONIO_PROJECT_KEY`.
- change the `forward` key in agent.yml to point to the HTTPS endpoint of your application or external site
