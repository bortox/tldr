---
author: ['Thamaraiselvam']
date: 1601982194
title: "lt, TLDR Pages"
description: "lt, Localtunnel exposes your localhost to the world for easy testing and sharing."
categories: "common"
---
> More information: <https://github.com/localtunnel/localtunnel>.

- Start tunnel from a specific port:

```bash
lt --port 8000
```

- Specify the upstream server doing the forwarding:

```bash
lt --port 8000 --host host
```

- Request a specific subdomain:

```bash
lt --port 8000 --subdomain subdomain
```

- Print basic request info:

```bash
lt --port 8000 --print-requests
```

- Open the tunnel URL in the default web browser:

```bash
lt --port 8000 --open
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Thamaraiselvam](mailto:thamaraiselvam@live.com) | lt: add page (#4390) | 2020-10-06T13:03:14 | [5265ed31b3c9](https://github.com/tldr-pages/tldr/commit/5265ed31b3c95a5bae0d4927e4f6abdf08f46d45)

