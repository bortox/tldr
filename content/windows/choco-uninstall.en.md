---
author: ['Marco Bonelli', 'pxgamer', 'Owen Voke']
date: 1559564381
title: "choco uninstall, TLDR Pages"
description: "choco uninstall, Uninstall one or more packages with Chocolatey."
categories: "windows"
---
> More information: <https://chocolatey.org/docs/commands-uninstall>.

- Uninstall one or more space-separated packages:

```bash
choco uninstall package(s)
```

- Uninstall a specific version of a package:

```bash
choco uninstall package --version version
```

- Confirm all prompts automatically:

```bash
choco uninstall package --yes
```

- Remove all dependencies when uninstalling:

```bash
choco uninstall package --remove-dependencies
```

- Uninstall all packages:

```bash
choco uninstall all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | choco-uninstall: add link to homepage | 2019-03-20T06:53:44 | [5a45ebe87465](https://github.com/tldr-pages/tldr/commit/5a45ebe87465d6f66c202870c75385bea5ef95e7)
[Owen Voke](mailto:owzie123@gmail.com) | choco-uninstall: add page (#2029) | 2018-03-14T00:33:01 | [eff392c0be60](https://github.com/tldr-pages/tldr/commit/eff392c0be60d733b416936e499b5c1061bbbcbb)

