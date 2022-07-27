---
author: ['Max Xu', 'Agniva De Sarker', 'Fabian', 'CleanMachine1', 'Lucas Gabriel Schneider']
date: 1626023849
title: "update-alternatives, TLDR Pages"
description: "update-alternatives, A convenient tool for maintaining symbolic links to determine default commands."
categories: "linux"
---
> More information: <https://manned.org/update-alternatives>.

- Add a symbolic link:

```bash
sudo update-alternatives --install path/to/symlink command_name path/to/command_binary priority
```

- Configure a symbolic link for `java`:

```bash
sudo update-alternatives --config java
```

- Remove a symbolic link:

```bash
sudo update-alternatives --remove java /opt/java/jdk1.8.0_102/bin/java
```

- Display information about a specified command:

```bash
update-alternatives --display java
```

- Display all commands and their current selection:

```bash
update-alternatives --get-selections
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | linux/u*: add links (#6190) | 2021-07-11T19:17:29 | [3ac60f1062ba](https://github.com/tldr-pages/tldr/commit/3ac60f1062ba714b493cee9c4e413901867c9f93)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Fabian](mailto:folfy@users.noreply.github.com) | update-alternatives: Added hint for showing all commands #2448 (#2448) | 2018-10-16T19:30:40 | [24bd33656030](https://github.com/tldr-pages/tldr/commit/24bd33656030925672c62dbe6540cce1f6b60600)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | update-alternatives: simplify descriptions | 2017-10-24T06:33:41 | [c08b50547782](https://github.com/tldr-pages/tldr/commit/c08b50547782380482f4cd7cc8eba105bb9c2f03)
[Max Xu](mailto:xuhuan@live.cn) | Update update-alternatives.md | 2017-10-24T04:22:25 | [ee39bfaeaff5](https://github.com/tldr-pages/tldr/commit/ee39bfaeaff5d585aa5007247ef41562ded1c766)
[Max Xu](mailto:xuhuan@live.cn) | Update update-alternatives.md Add both generic expression and a concrete examples. | 2017-10-24T04:17:54 | [1d7ad860ffcf](https://github.com/tldr-pages/tldr/commit/1d7ad860ffcf8f50d58d482e9e5ee92edbe35129)
[Max Xu](mailto:xuhuan@live.cn) | Update update-alternatives.md | 2017-10-23T06:09:28 | [5c9ab17a1988](https://github.com/tldr-pages/tldr/commit/5c9ab17a19881d053814fe9b661333ffbd5de781)
[Max Xu](mailto:xuhuan@live.cn) | Update update-alternatives.md | 2017-10-22T13:54:39 | [59a42c5798c8](https://github.com/tldr-pages/tldr/commit/59a42c5798c80d327189f1a0a7b93573e843ecf2)
[Max Xu](mailto:xuhuan@live.cn) | Update update-alternatives.md | 2017-10-15T15:27:39 | [5791f2efc7d7](https://github.com/tldr-pages/tldr/commit/5791f2efc7d7b93758999b744830d812dca6c6ca)
[Max Xu](mailto:xuhuan@live.cn) | update-alternatives: add page | 2017-10-13T09:42:02 | [db39479bb83b](https://github.com/tldr-pages/tldr/commit/db39479bb83baa47777ffb74c6a7798c4c43e1d6)

