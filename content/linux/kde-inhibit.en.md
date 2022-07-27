---
author: ['Axel Navarro', 'Seth Falco', 'Emily Grace Seville']
date: 1647882468
title: "kde-inhibit, TLDR Pages"
description: "kde-inhibit, Inhibit various desktop functions while a command runs."
categories: "linux"
---
> More information: <https://invent.kde.org/plasma/kde-cli-tools/-/blob/master/kdeinhibit/main.cpp>.

- Inhibit power management:

```bash
kde-inhibit --power command command_arguments
```

- Inhibit screen saver:

```bash
kde-inhibit --screenSaver command command_arguments
```

- Launch VLC, and inhibit color correction (night mode) while it's running:

```bash
kde-inhibit --colorCorrect vlc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Axel Navarro](mailto:navarroaxel@gmail.com) | kde-inhibit: add page (#4976) | 2020-12-27T11:21:13 | [f609506037fd](https://github.com/tldr-pages/tldr/commit/f609506037fd13a618dc6697e6bc6d281545ed93)

