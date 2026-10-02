# caddy-cf

[Caddy](https://caddyserver.com) built with two plugins:

- [`caddy-docker-proxy`](https://github.com/lucaslorentz/caddy-docker-proxy): configure routes from Docker labels
- [`caddy-dns/cloudflare`](https://github.com/caddy-dns/cloudflare): ACME DNS-01 challenges via Cloudflare

Published to `ghcr.io/paolonarvaez/caddy-cf` and rebuilt weekly.

| Tag | Source |
|---|---|
| `latest`, `sha-<rev>` | default branch |
| `branch-<name>` | any other branch |

The container runs `caddy docker-proxy --caddyfile-path /etc/caddy/Caddyfile`.
