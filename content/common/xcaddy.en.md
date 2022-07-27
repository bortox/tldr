---
author: ['Owen Voke']
date: 1597592081
title: "xcaddy, TLDR Pages"
description: "xcaddy, The custom build tool for the Caddy Web Server."
categories: "common"
---
> More information: <https://github.com/caddyserver/xcaddy>.

- Build Caddy server from source:

```bash
xcaddy build
```

- Build Caddy server with a specific version (defaults to latest):

```bash
xcaddy build version
```

- Build Caddy with a specific module:

```bash
xcaddy build --with module_name
```

- Build Caddy and output to a specific file:

```bash
xcaddy build --output path/to/file
```

- Build and run Caddy for a development plugin in the current directory:

```bash
xcaddy run
```

- Build and run Caddy for a development plugin using a specific Caddy config:

```bash
xcaddy run --config path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | xcaddy: add page (#4259) | 2020-08-16T17:34:41 | [82cc25ba32bb](https://github.com/tldr-pages/tldr/commit/82cc25ba32bbe8d070d8a36526b10923259f2ac6)

