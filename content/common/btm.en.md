---
author: ['Pepe Doval', 'Seth Falco']
date: 1629050349
title: "btm"
description: "btm, An alternative to `top`."
categories: "common"
---
> Aims to be lightweight, cross-platform and more graphical than `top`.

> More information: <https://github.com/ClementTsang/bottom>.

- Show the default layout (CPU, memory, temperatures, disk, network, and processes):

```bash
btm
```

- Enable basic mode, removing charts and condensing data (similar to `top`):

```bash
btm --basic
```

- Use big dots instead of small ones in charts:

```bash
btm --dot_marker
```

- Show also battery charge and health status:

```bash
btm --battery
```

- Refresh every 250 milliseconds and show the last 30 seconds in the charts:

```bash
btm --rate 250 --default_time_value 30000
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Pepe Doval](mailto:pepellou@gmail.com) | btm: add page (#4300) btm is a cross-platform graphical process/system monitor with a customizable interface and a multitude of [...] | 2020-09-05T00:49:00 | [adcce024e6ba](https://github.com/tldr-pages/tldr/commit/adcce024e6ba44eeff9b93d44068826d5d766a0c)

