---
author: ['CleanMachine1', 'Max Xu', 'Lucas Gabriel Schneider']
date: 1626023849
title: "update-rc.d, TLDR Pages"
description: "update-rc.d, Install and remove services which are System-V style init script links."
categories: "linux"
---
> Init scripts are in the `/etc/init.d/`.

> More information: <https://manned.org/update-rc.d>.

- Install a service:

```bash
update-rc.d mysql defaults
```

- Enable a service:

```bash
update-rc.d mysql enable
```

- Disable a service:

```bash
update-rc.d mysql disable
```

- Forcibly remove a service:

```bash
update-rc.d -f mysql remove
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | linux/u*: add links (#6190) | 2021-07-11T19:17:29 | [3ac60f1062ba](https://github.com/tldr-pages/tldr/commit/3ac60f1062ba714b493cee9c4e413901867c9f93)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Max Xu](mailto:xuhuan@live.cn) | update-rc.d: add page (#1412) | 2017-07-05T22:46:58 | [04e9d13b70f2](https://github.com/tldr-pages/tldr/commit/04e9d13b70f2e87dd16e1672fcf79dd145602ae8)

