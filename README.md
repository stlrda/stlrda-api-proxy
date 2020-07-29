# stlrda-api-proxy
Master Caddy Proxy for Running and Maintaining Multiple API Docker Containers Behind HTTPS

## What does this do?
The `docker-compose.yml` defines a set of services (Docker containers) and the `Caddyfile` configures a **secure** reverse proxy such that we can host many services on a single server and route to them using Caddy as a proxy. Each new service needs to be added to the docker compose file and a route defined in the Caddyfile to proxy the server.
