---
author: ['Lucas Gabriel Schneider', 'bl-ue', 'Owen Voke', 'Emily Grace Seville']
date: 1637602652
title: "cmd, TLDR Pages"
description: "cmd, The Windows command interpreter."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/cmd>.

- Start an interactive shell session:

```bash
cmd
```

- Execute a [c]ommand:

```bash
cmd /c "command"
```

- Execute a script:

```bash
cmd path/to/file.bat
```

- Execute a command and then enter an interactive shell:

```bash
cmd /k "command"
```

- Start an interactive shell session where `echo` is disabled in command output:

```bash
cmd /q
```

- Start an interactive shell session with delayed [v]ariable expansion enabled or disabled:

```bash
cmd /v:on|off
```

- Start an interactive shell session with command [e]xtensions enabled or disabled:

```bash
cmd /e:on|off
```

- Start an interactive shell session with used Unicode encoding:

```bash
cmd /u
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | cmd: update page (#7417) | 2021-11-22T18:37:32 | [e33298ff7556](https://github.com/tldr-pages/tldr/commit/e33298ff7556343c1e19a7c6413b440c27c938f8)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Owen Voke](mailto:owzie123@gmail.com) | cmd: add page (#2345) | 2018-09-26T22:01:42 | [e7beabd5d77b](https://github.com/tldr-pages/tldr/commit/e7beabd5d77b517cac98c7005b0b37b4511cdc6e)

