---
author: ['Ivan Aracki', 'Seth Falco', 'Marco Bonelli']
date: 1629050349
title: "trawl"
description: "trawl, Prints out network interface information to the console, much like ifconfig/ipconfig/ip/ifdata."
categories: "common"
---
> More information: <https://github.com/robphoenix/trawl>.

- Show column names:

```bash
trawl -n
```

- Filter interface names using a case-insensitive regular expression:

```bash
trawl -f wi
```

- Get a list of available interfaces:

```bash
trawl -i
```

- Include the loopback interface:

```bash
trawl -l
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | trawl: add page (#2893) | 2019-04-12T13:59:29 | [a8d2a344b587](https://github.com/tldr-pages/tldr/commit/a8d2a344b5879b5eb50c1584ac3df67762734a98)

