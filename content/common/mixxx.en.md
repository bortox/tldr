---
author: ['Janek', 'bl-ue', 'Seth Falco']
date: 1629050349
title: "mixxx"
description: "mixxx, Free and open source cross-platform DJ software."
categories: "common"
---
> More information: <https://mixxx.org/manual/latest/chapters/appendix.html#command-line-options>.

- Start the Mixxx GUI in fullscreen:

```bash
mixxx --fullScreen
```

- Start in safe developer mode to debug a crash:

```bash
mixxx --developer --safeMode
```

- Debug a malfunction:

```bash
mixxx --debugAssertBreak --developer --loglevel trace
```

- Start Mixxx using the specified settings file:

```bash
mixxx --resourcePath mixxx/res/controllers --settingsPath path/to/settings-file
```

- Debug a custom controller mapping:

```bash
mixxx --controllerDebug --resourcePath path/to/mapping-directory
```

- Show command-line help:

```bash
mixxx --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Janek](mailto:xerusx@pm.me) | mixxx: add common page (#4959) | 2020-12-19T19:56:00 | [7a95a5180fc6](https://github.com/tldr-pages/tldr/commit/7a95a5180fc6850fa2ba8ebd2e81b71b17673185)

