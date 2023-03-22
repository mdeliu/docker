# Docker
Docker and Docker-Compose files

### Info #1
- install Docker & Docker Compose on Linux host
- create network: ```sudo docker network caddy_net```
- Caddy as reverse proxy
- Apache Weblog
- Nextcloud
- Vaultwarden

### Info #2
Setup could be:
VPS <-> Cloudflare as nameserver and proxy <-> Caddy <-> Redirect to Docker containers

### Info #3
Didn't worked with environment files due to simplicity, feel free to modify the files as needed.
