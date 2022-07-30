---
author: ['Hayden Schiff', 'pxgamer', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "redshift"
description: "redshift, Adjust the color temperature of your screen according to your surroundings."
categories: "common"
---
> More information: <http://jonls.dk/redshift>.

- Turn on Redshift with 5700K temperature during day and 3600K at night:

```bash
redshift -t 5700:3600
```

- Turn on Redshift with a manually specified custom location:

```bash
redshift -l latitude:longitude
```

- Turn on Redshift with 70% screen brightness during day and 40% brightness at night:

```bash
redshift -b 0.7:0.4
```

- Turn on Redshift with custom gamma levels (between 0 and 1):

```bash
redshift -g red:green:blue
```

- Turn on Redshift with a constant unchanging color temperature:

```bash
redshift -O temperature
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | redshift: add link to homepage | 2019-05-29T14:41:10 | [c8ba5df0ba3c](https://github.com/tldr-pages/tldr/commit/c8ba5df0ba3cab6f4c3ba5e6be141b6d322f7d33)
[Hayden Schiff](mailto:oxguy3@gmail.com) | redshift: removed `-r` example | 2016-01-22T05:08:52 | [cc00b3b1f2f6](https://github.com/tldr-pages/tldr/commit/cc00b3b1f2f6c233ebb672bba796dc3d5c75cb68)
[Hayden Schiff](mailto:oxguy3@gmail.com) | redshift: add page | 2016-01-22T01:07:03 | [16a630de2181](https://github.com/tldr-pages/tldr/commit/16a630de2181cf70f37433fc2ea672faca2ee2d4)

