---
author: ['Leon Feng', 'UnButtun']
date: 1660998827
title: "pnpm"
description: "pnpm, Fast, disk space efficient package manager for Node.js."
categories: "common"
---
> Manage Node.js projects and their module dependencies.

> More information: <https://pnpm.io>.

- Create a `package.json` file:

```bash
pnpm init
```

- Download all the packages listed as dependencies in `package.json`:

```bash
pnpm install
```

- Download a specific version of a package and add it to the list of dependencies in `package.json`:

```bash
pnpm add module_name@version
```

- Download a package and add it to the list of [D]ev dependencies in `package.json`:

```bash
pnpm add -D module_name
```

- Download a package and install it [g]lobally:

```bash
pnpm add -g module_name
```

- Uninstall a package and remove it from the list of dependencies in `package.json`:

```bash
pnpm remove module_name
```

- Print a tree of locally installed modules:

```bash
pnpm list
```

- List top-level [g]lobally installed modules:

```bash
pnpm list -g --depth=0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Leon Feng](mailto:leonfeng@proton.me) | pnpm: update page (#8384) | 2022-08-20T14:33:47 | [f3c12cc75b23](https://github.com/tldr-pages/tldr/commit/f3c12cc75b23c8a8c036023cdf1ac0816ec9b34a)
[UnButtun](mailto:79936503+Unbuttun@users.noreply.github.com) | pnpm, pnpx: add page (#5863) | 2021-05-03T17:56:31 | [5ba22052b74d](https://github.com/tldr-pages/tldr/commit/5ba22052b74d11926b66444e53014e5c74630fe1)

