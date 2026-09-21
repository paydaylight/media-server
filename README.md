# Media server

### This project mashes together immich/jellyfin/samba in one compose file for ease of use

Checkout .env.example for required env variables

```
cp .env.example .env
```

And run

```
docker compose up -d
```

Tailscale is the only app that is not containerised - it is much easier to install on host machine compared to nginx-sidecar approach in compose file

[How to install tailscale](https://tailscale.com/docs/how-to/quickstart)
