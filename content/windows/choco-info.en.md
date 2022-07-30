---
author: ['pxgamer', 'Marco Bonelli']
date: 1559564381
title: "choco info"
description: "choco info, Display detailed information about a package with Chocolatey."
categories: "windows"
---
> More information: <https://chocolatey.org/docs/commands-info>.

- Display information on a specific package:

```bash
choco info package
```

- Display information for a local package only:

```bash
choco info package --local-only
```

- Specify a custom source to receive packages information from:

```bash
choco info package --source source_url|alias
```

- Provide a username and password for authentication:

```bash
choco info package --user username --password password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | choco-info: add link to homepage | 2019-03-20T06:53:44 | [a4451e6751d9](https://github.com/tldr-pages/tldr/commit/a4451e6751d97da21a5c9d91b1cfd9a15cee43e1)
[pxgamer](mailto:owzie123@gmail.com) | choco-info: add page | 2018-03-23T05:24:41 | [44b176c6b95b](https://github.com/tldr-pages/tldr/commit/44b176c6b95b900d24facc5b501860b5654b8e88)

