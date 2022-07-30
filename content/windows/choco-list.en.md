---
author: ['Owen Voke', 'pxgamer', 'Marco Bonelli']
date: 1559564381
title: "choco list"
description: "choco list, Display a list of packages with Chocolatey."
categories: "windows"
---
> More information: <https://chocolatey.org/docs/commands-list>.

- Display all available packages:

```bash
choco list
```

- Display all locally installed packages:

```bash
choco list --local-only
```

- Display a list including local programs:

```bash
choco list --include-programs
```

- Display only approved packages:

```bash
choco list --approved-only
```

- Specify a custom source to display packages from:

```bash
choco list --source source_url|alias
```

- Provide a username and password for authentication:

```bash
choco list --user username --password password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | choco-list: add link to homepage | 2019-03-20T06:53:44 | [db5bd26512ae](https://github.com/tldr-pages/tldr/commit/db5bd26512aecc7463843a7b6d4bc5e409cfad5e)
[Owen Voke](mailto:owzie123@gmail.com) | choco-list: add page (#2046) | 2018-03-27T11:18:01 | [ac22ef25d103](https://github.com/tldr-pages/tldr/commit/ac22ef25d10330e5e8fef4cd2d7ccd8a644f49fc)

