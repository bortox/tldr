---
author: ['John Ingram', 'Lucas Gabriel Schneider']
date: 1612112718
title: "redis-server, TLDR Pages"
description: "redis-server, Persistent key-value database."
categories: "common"
---
> More information: <https://redis.io>.

- Start Redis server, using the default port (6379), and write logs to stdout:

```bash
redis-server
```

- Start Redis server, using the default port, as a background process:

```bash
redis-server --daemonize yes
```

- Start Redis server, using the specified port, as a background process:

```bash
redis-server --port port --daemonize yes
```

- Start Redis server with a custom configuration file:

```bash
redis-server path/to/redis.conf
```

- Start Redis server with verbose logging:

```bash
redis-server --loglevel warning|notice|verbose|debug
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[John Ingram](mailto:readparse@users.noreply.github.com) | redis-server: add page (#4356) | 2020-10-05T13:11:57 | [73c6a856e2da](https://github.com/tldr-pages/tldr/commit/73c6a856e2dac193470ebfe04b5084c0c82d8315)

