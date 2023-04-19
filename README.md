# Tailscale as a container

Use Compose to deploy a Tailscale container:

```
$ docker compose up
$ docker-compose exec tailscaled tailscale up --authkey=${TS_AUTHKEY} --hostname=${HOSTNAME}
$ docker-compose exec tailscaled tailscale status
```