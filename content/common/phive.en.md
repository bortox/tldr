---
author: ['pxgamer', 'Owen Voke']
date: 1559328460
title: "phive, TLDR Pages"
description: "phive, The Phar Installation and Verification Environment for secure PHP application deployment."
categories: "common"
---
> More information: <https://phar.io>.

- Display a list of available aliased Phars:

```bash
phive list
```

- Install a specified Phar to the local directory:

```bash
phive install alias|url
```

- Install a specified Phar globally:

```bash
phive install alias|url --global
```

- Install a specified Phar to a target directory:

```bash
phive install alias|url --target path/to/directory
```

- Update all Phar files to the latest version:

```bash
phive update
```

- Remove a specified Phar file:

```bash
phive remove alias|url
```

- Remove unused Phar files:

```bash
phive purge
```

- List all available commands:

```bash
phive help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | phive: add link to homepage | 2019-05-31T20:47:40 | [9776a3583c7c](https://github.com/tldr-pages/tldr/commit/9776a3583c7cab021cda277b9c508b277abbb495)
[Owen Voke](mailto:owzie123@gmail.com) | phive: add page (#1956) | 2018-02-03T11:32:08 | [c45abeb5ee57](https://github.com/tldr-pages/tldr/commit/c45abeb5ee57583740e801f12a7d0d2c29ed8f70)

