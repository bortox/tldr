---
author: ['Maxim Muzafarov', 'Jérémy Lal', 'Kyle', 'Ruben Vereecken', 'Amine Hajyoussef']
date: 1629747204
title: "host"
description: "host, Lookup Domain Name Server."
categories: "common"
---
> More information: <https://manned.org/host>.

- Lookup A, AAAA, and MX records of a domain:

```bash
host domain
```

- Lookup a field (CNAME, TXT,...) of a domain:

```bash
host -t field domain
```

- Reverse lookup an IP:

```bash
host ip_address
```

- Specify an alternate DNS server to query:

```bash
host domain 8.8.8.8
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Maxim Muzafarov](mailto:m.muzafarov@gmail.com) | host: add alternate dns server example (#2435) | 2018-10-16T13:56:02 | [2e986aa890cb](https://github.com/tldr-pages/tldr/commit/2e986aa890cb784ce2dcc3a676ed3cf3dd9dbae5)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Amine Hajyoussef](mailto:hajyoussef.amine@gmail.com) | consistent markup | 2015-12-31T14:11:18 | [3fe8681e19ac](https://github.com/tldr-pages/tldr/commit/3fe8681e19acf79351509fb46b1988a0ab64397f)
[Jérémy Lal](mailto:kapouer@melix.org) | Add host | 2015-12-31T01:55:00 | [a41b1c087553](https://github.com/tldr-pages/tldr/commit/a41b1c087553abee07706f02a2af3c71f6741804)

