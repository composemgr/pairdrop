# Pairdrop

A self-hosted pairdrop application.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/pairdrop/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/pairdrop" ~/.local/srv/docker/pairdrop
cd ~/.local/srv/docker/pairdrop
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install pairdrop
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
