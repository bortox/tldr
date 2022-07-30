---
author: ['pxgamer', 'Lucas Gabriel Schneider', 'Seth Falco', 'David']
date: 1629050349
title: "hostess"
description: "hostess, An idempotent command-line utility for managing the `/etc/hosts` file."
categories: "common"
---
> More information: <https://github.com/cbednarski/hostess>.

- List domains, target IP addresses and on/off status:

```bash
hostess list
```

- Add a domain pointing to your machine to your hosts file:

```bash
hostess add local.example.com 127.0.0.1
```

- Remove a domain from your hosts file:

```bash
hostess del local.example.com
```

- Disable a domain (but don't remove it):

```bash
hostess off local.example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[pxgamer](mailto:owzie123@gmail.com) | hostess: add link to homepage | 2019-06-07T23:58:59 | [49e2e9bb5a97](https://github.com/tldr-pages/tldr/commit/49e2e9bb5a978b79f3a6527a95fa95352b211dc7)
[David](mailto:david.bialik@gmail.com) | hostess: add page (#2541) | 2018-11-03T11:29:54 | [fb6c361c7c54](https://github.com/tldr-pages/tldr/commit/fb6c361c7c544c223013468a0f63140dbc37fa90)

