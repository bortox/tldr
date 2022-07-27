---
author: ['pixel']
date: 1644038705
title: "lerna, TLDR Pages"
description: "lerna, A tool for managing JavaScript projects with multiple packages."
categories: "common"
---
> More information: <https://lerna.js.org>.

- Initialize project files (`lerna.json`, `package.json`, `.git`, etc.):

```bash
lerna init
```

- Install all external dependencies of each package and symlink together local dependencies:

```bash
lerna bootstrap
```

- Run a specific script for every package that contains it in its `package.json`:

```bash
lerna run script
```

- Execute an arbitrary shell command in every package:

```bash
lerna exec -- ls
```

- Publish all packages that have changed since the last release:

```bash
lerna publish
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | lerna: add page (#7742) Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2022-02-05T06:25:05 | [b58b87ff748a](https://github.com/tldr-pages/tldr/commit/b58b87ff748afce0afc63e0b61948ae110824b4e)

