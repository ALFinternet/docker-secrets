# docker-secrets
Script for setting up docker secrets

Use:

1. Copy compose.yaml and .env to your host:
```bash
rm -fr ~/appdata/docker_files/docker-secrets
git clone https://github.com/ALFinternet/docker-secrets.git ~/appdata/docker_files/docker-secrets
```

2. Deploy
```bash
docker compose -p docker-secrets -f ~/appdata/docker_files/docker-secrets/compose.yaml --env-file ~/appdata/docker_files/docker-secrets/.env up -d
```