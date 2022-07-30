---
author: ['Schneider', 'Ismail Arafa', 'Seth Falco', 'Marco Bonelli']
date: 1629050349
title: "browser-sync"
description: "browser-sync, Starts local web server that updates browser on file changes."
categories: "common"
---
> More information: <https://browsersync.io/docs/command-line>.

- Start a server from a specific directory:

```bash
browser-sync start --server path/to/directory --files path/to/directory
```

- Start a server from local directory, watching all CSS files in a directory:

```bash
browser-sync start --server --files 'path/to/directory/*.css'
```

- Create configuration file:

```bash
browser-sync init
```

- Start browser-sync from config file:

```bash
browser-sync start --config config_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | browser-sync.md: add homepage | 2019-04-12T14:41:22 | [25b9d96d081e](https://github.com/tldr-pages/tldr/commit/25b9d96d081ea5a5475e7f9e8091b6e7bcbe53c9)
[Ismail Arafa](mailto:ismailarafa18@gmail.com) | Create browser-sync.md (#1287) | 2017-04-06T13:41:22 | [ece6982be9a3](https://github.com/tldr-pages/tldr/commit/ece6982be9a3603ff6c625fd87cbfc5ef829dcb5)

