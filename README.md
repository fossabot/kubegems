[![.github/workflows/build.yml](https://github.com/kubegems/gems/actions/workflows/build.yml/badge.svg)](https://github.com/kubegems/gems/actions/workflows/build.yml)

# kubegem

under construction ... 🚧 🚧 🚧

## Getting started

[quick-start](docs/quick-start.md)

## Development

### Run local

1. `make build` 
2. `./bin/kubegems service gencfg > config/config.yaml`
3. `cd scripts && bash generate-tls-certs.sh`
4. `./bin/kubegems service`

### Debug by vscode

```json
{
  "name": "service",
  "type": "go",
  "request": "launch",
  "mode": "debug",
  "program": "${workspaceFolder}/cmd",
  "cwd": "${workspaceFolder}", 
  "args": ["service"]
}
```
