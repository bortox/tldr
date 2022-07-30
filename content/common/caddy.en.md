---
author: ['ddgond']
date: 1623506493
title: "caddy"
description: "caddy, A powerful, enterprise-ready, open source web server with automatic HTTPS, written in Go."
categories: "common"
---
> More information: <https://caddyserver.com>.

- Start Caddy in the foreground:

```bash
caddy run
```

- Start Caddy with the specified Caddyfile:

```bash
caddy run --config path/to/Caddyfile
```

- Start Caddy in the background:

```bash
caddy start
```

- Stop a background Caddy process:

```bash
caddy stop
```

- Run a simple file server on the specified port with a browsable interface:

```bash
caddy file-server --listen :8000 --browse
```

- Run a reverse proxy server:

```bash
caddy reverse-proxy --from :80 --to localhost:8000
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[ddgond](mailto:dadangond@protonmail.com) | caddy: add page (#6115) | 2021-06-12T16:01:33 | [cd5fccfcbb23](https://github.com/tldr-pages/tldr/commit/cd5fccfcbb23e87d4908c810b2b5cf593f6243e9)

