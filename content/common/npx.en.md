---
author: ['Axel Navarro', '白霁', 'pxgamer']
date: 1645185102
title: "npx"
description: "npx, Execute binaries from `npm` packages."
categories: "common"
---
> More information: <https://github.com/npm/npx>.

- Execute the binary from a given npm module:

```bash
npx module_name command_arguments
```

- In case a package has multiple binaries, specify the package name along with the binary:

```bash
npx --package package_name module_name
```

- Run a command if existis in the current path or in `node_modules/.bin`:

```bash
npx --no-install command command_arguments
```

- Execute the binary from a given npm module suppressing any output from `npx` itself:

```bash
npx --quiet module_name command_arguments
```

- Display help:

```bash
npx --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | npx: add --no-install and --quiet examples (#7747) | 2022-02-18T12:51:42 | [c8a26c33e477](https://github.com/tldr-pages/tldr/commit/c8a26c33e477312371940a7243019e4711881773)
[Axel Navarro](mailto:navarroaxel@gmail.com) | *: use author link instead of npm package (#7730) | 2022-02-02T19:43:21 | [c2c16f61acbd](https://github.com/tldr-pages/tldr/commit/c2c16f61acbdca1933961fbbc20a80bdae76ece5)
[pxgamer](mailto:owzie123@gmail.com) | npx: add link to homepage | 2019-06-04T21:29:40 | [fa3be19f5f5d](https://github.com/tldr-pages/tldr/commit/fa3be19f5f5d72ab4a06e7c9f1ac9608edf79ac0)
[白霁](mailto:1041874421@qq.com) | npx: add page (#1857) | 2018-01-06T14:19:04 | [89ceaeeddb8d](https://github.com/tldr-pages/tldr/commit/89ceaeeddb8d441541fb7cab8634247f9a416177)

