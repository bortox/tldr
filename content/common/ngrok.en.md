---
author: ['Marco Bonelli', 'Ivan Aracki']
date: 1559564381
title: "ngrok, TLDR Pages"
description: "ngrok, Reverse proxy that creates a secure tunnel from a public endpoint to a locally running web service."
categories: "common"
---
> More information: <https://ngrok.com>.

- Expose a local HTTP service on a given port:

```bash
ngrok http 80
```

- Expose a local HTTP service on a specific host:

```bash
ngrok http foo.dev:80
```

- Expose a local HTTPS server:

```bash
ngrok http https://localhost
```

- Expose TCP traffic on a given port:

```bash
ngrok tcp 22
```

- Expose TLS traffic for a specific host and port:

```bash
ngrok tls -hostname=foo.com 443
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | ngrok: add page (#3003) | 2019-05-10T16:08:21 | [976162161601](https://github.com/tldr-pages/tldr/commit/976162161601dedc9cf16d7f780108e0ab836f84)

