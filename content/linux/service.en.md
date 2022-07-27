---
author: ['fuerbringer', 'Lucas Gabriel Schneider', 'Ray Voice', 'Emily Grace Seville']
date: 1647882468
title: "service, TLDR Pages"
description: "service, Manage services by running init scripts."
categories: "linux"
---
> The full script path should be omitted (`/etc/init.d/` is assumed).

> More information: <https://manned.org/service>.

- List the name and status of all services:

```bash
service --status-all
```

- Start/Stop/Restart/Reload service (start/stop should always be available):

```bash
service service_name start|stop|restart|reload
```

- Do a full restart (runs script twice with start and stop):

```bash
service service_name --full-restart
```

- Show the current status of a service:

```bash
service service_name status
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Ray Voice](mailto:33094591+Ray6464@users.noreply.github.com) | service: move --status-all example (#4398) | 2020-10-06T20:44:12 | [660159209892](https://github.com/tldr-pages/tldr/commit/66015920989207570d796ea3af0bd76b01a44bff)
[fuerbringer](mailto:severin@protonmail.ch) | Changed description to be more informative. | 2016-11-16T08:11:54 | [903936888ade](https://github.com/tldr-pages/tldr/commit/903936888ade619f418be32c034bbcf96c6b6f3f)
[fuerbringer](mailto:severin@protonmail.ch) | Added assumed path to description and corrected command format. | 2016-11-16T08:11:54 | [b1d02e0a6a89](https://github.com/tldr-pages/tldr/commit/b1d02e0a6a89c477f2e607b0a7791d9436137a9a)
[fuerbringer](mailto:severin@protonmail.ch) | service: add page | 2016-11-16T08:11:54 | [7bf5a9a5f337](https://github.com/tldr-pages/tldr/commit/7bf5a9a5f337b9bdd609e80023b926fbbd71ca74)

