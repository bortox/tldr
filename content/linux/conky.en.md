---
author: ['Iván', 'Seth Falco', 'Maharaj Fawwaz A. Yusran']
date: 1629050349
title: "conky, TLDR Pages"
description: "conky, Light-weight system monitor for X."
categories: "linux"
---
> More information: <https://github.com/brndnmtthws/conky>.

- Launch with default, built-in config:

```bash
conky
```

- Create a new default config:

```bash
conky -C > ~/.conkyrc
```

- Launch Conky with a given config file:

```bash
conky -c path/to/config
```

- Start in the background (daemonize):

```bash
conky -d
```

- Align Conky on the desktop:

```bash
conky -a {top,bottom,middle}_{left,right,middle}
```

- Pause for 5 seconds at startup before launching:

```bash
conky -p 5
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Iván](mailto:ivan@ivanhercaz.com) | conky: add more information link (#3682) | 2019-12-23T17:33:57 | [b0c5a551adf3](https://github.com/tldr-pages/tldr/commit/b0c5a551adf3c81f4f2f5ae6faec329fe9e8027b)
[Maharaj Fawwaz A. Yusran](mailto:faww4zintelgent4@gmail.com) | conky: add page (#2135) * conky: add page * Remove prefixing, put variable in tokens, change `-p` and `-a` descriptions * Fix [...] | 2018-06-06T18:40:37 | [cfa0520aa627](https://github.com/tldr-pages/tldr/commit/cfa0520aa62763be7cddd607e0a8594e517fc418)

