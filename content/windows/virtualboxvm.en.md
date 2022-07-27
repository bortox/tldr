---
author: ['Marco Bonelli', 'bl-ue']
date: 1621541621
title: "virtualboxvm, TLDR Pages"
description: "virtualboxvm, The VirtualBox virtual machine management CLI."
categories: "windows"
---
> More information: <https://www.virtualbox.org>.

- Start a virtual machine:

```bash
virtualboxvm --startvm name|uuid
```

- Start a virtual machine in fullscreen mode:

```bash
virtualboxvm --startvm name|uuid --fullscreen
```

- Mount the specified DVD image file:

```bash
virtualboxvm --startvm name|uuid --dvd path/to/image_file
```

- Display a command-line window with debug information:

```bash
virtualboxvm --startvm name|uuid --debug-command-line
```

- Start a virtual machine in a paused state:

```bash
virtualboxvm --startvm name|uuid --start-paused
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | virtualboxvm: move to windows platform. (#3069) | 2019-05-31T15:13:04 | [013160fcf31c](https://github.com/tldr-pages/tldr/commit/013160fcf31c727279777a0f0fe47eda541b24af)

