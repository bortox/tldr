---
author: ['Lucas Gabriel Schneider', 'Seth Falco', 'Owen Voke']
date: 1629050349
title: "pathping, TLDR Pages"
description: "pathping, A trace route tool combining features of `ping` and `tracert`."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/pathping>.

- Ping and trace the route to a host:

```bash
pathping hostname
```

- Do not perform reverse lookup of IP address to hostname:

```bash
pathping hostname -n
```

- Specify the maximum number of hops to search for the target (the default is 30):

```bash
pathping hostname -h max_hops
```

- Specify the milliseconds to wait between pings (the default is 240):

```bash
pathping hostname -p time
```

- Specify the number of queries per hop (the default is 100):

```bash
pathping hostname -q queries
```

- Force IPV4 usage:

```bash
pathping hostname -4
```

- Force IPV6 usage:

```bash
pathping hostname -6
```

- Display detailed usage information:

```bash
pathping /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | pathping: add page (#2077) | 2018-04-21T10:43:29 | [2d9ecbd38855](https://github.com/tldr-pages/tldr/commit/2d9ecbd38855c3797b21dad2f6e63c0418776811)

