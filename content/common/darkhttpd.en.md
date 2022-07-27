---
author: ['pxgamer', 'Arun Isaac']
date: 1560056064
title: "darkhttpd, TLDR Pages"
description: "darkhttpd, Darkhttpd web server."
categories: "common"
---
> More information: <https://unix4lyfe.org/darkhttpd>.

- Start server serving the specified document root:

```bash
darkhttpd path/to/docroot
```

- Start server on specified port (port 8080 by default if running as non-root user):

```bash
darkhttpd path/to/docroot --port port
```

- Listen only on specified IP address (by default, the server listens on all interfaces):

```bash
darkhttpd path/to/docroot --addr ip_address
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | darkhttpd: add link to homepage | 2019-06-09T06:54:24 | [d4c9acf0430f](https://github.com/tldr-pages/tldr/commit/d4c9acf0430fab36d4735dab8d572781c6f202b9)
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | darkhttpd: add page (#2490) | 2018-10-25T00:59:41 | [278d1e798e15](https://github.com/tldr-pages/tldr/commit/278d1e798e15c51da75cc66beb526e59d3699506)

