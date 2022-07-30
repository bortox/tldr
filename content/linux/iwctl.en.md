---
author: ['D34DPlayer', 'bl-ue', 'Seth Falco']
date: 1629050349
title: "iwctl"
description: "iwctl, A command-line tool for controlling the iwd network supplicant."
categories: "linux"
---
> More information: <https://iwd.wiki.kernel.org/gettingstarted>.

- Start the interactive mode, in this mode you can enter the commands directly, with autocompletion:

```bash
iwctl
```

- Call general help:

```bash
iwctl --help
```

- Display your Wi-Fi stations:

```bash
iwctl station list
```

- Start looking for networks with a station:

```bash
iwctl station station scan
```

- Display the networks found by a station:

```bash
iwctl station station get-networks
```

- Connect to a network with a station, if credentials are needed they will be asked:

```bash
iwctl station station connect network_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[D34DPlayer](mailto:58138378+D34DPlayer@users.noreply.github.com) | iwctl: add page and French translation (#4594) | 2020-10-09T22:11:08 | [6c92ad98a9d5](https://github.com/tldr-pages/tldr/commit/6c92ad98a9d561cb4a0eb81336e648cd8e7e71f7)

