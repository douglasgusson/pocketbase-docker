# PocketBase Deploy

> [Host for free on Fly.io](https://github.com/pocketbase/pocketbase/discussions/537)

## Instalação Fly.io CLI

```bash
curl -L https://fly.io/install.sh | sh
```

### Fish Shell

```fish
# ~/.config/fish/config.fish

set -gx FLYCTL_INSTALL "/home/$USER/.fly"
set -gx PATH "$FLYCTL_INSTALL/bin" $PATH
``` 


## Docker

### Construção
```bash
docker build -t pocketbase .
```

### Execução
```bash
docker run -dp 8080:8080 pocketbase
```
