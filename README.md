# No-Code AI platform

No-Code / Low-Code AI platform using Flowise, LangFlow, JupyterHub and n8n on GKE.

## Setup

```bash
# install required tool dependencies via Brewfile
brew bundle

# create and bootstrap GKE cluster
task create-cluster
task create-secrets
task bootstrap-flux
```

## Maintainer

M.-Leander Reimer (@lreimer), <mario-leander.reimer@qaware.de>

## License

This software is provided under the MIT open source license, read the `LICENSE`
file for details.