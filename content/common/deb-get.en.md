---
author: ['walking-octopus']
date: 1657386000
title: "deb-get"
description: "deb-get, `apt-get` functionality for `.deb` packages published in third party repositories or via direct download."
categories: "common"
---
> Works with Linux distributions which use `apt-get`.

> More information: <https://github.com/wimpysworld/deb-get>.

- Update the list of available packages and versions:

```bash
sudo deb-get update
```

- Search for a given package:

```bash
sudo deb-get search package
```

- Show information about a package:

```bash
sudo deb-get show package
```

- Install a package, or update it to the latest available version:

```bash
sudo deb-get install package
```

- Remove a package (using `purge` instead also removes its configuration files):

```bash
sudo deb-get remove package
```

- Upgrade all installed packages to their newest available versions:

```bash
sudo deb-get upgrade
```

- List all available packages:

```bash
deb-get list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[walking-octopus](mailto:46994949+walking-octopus@users.noreply.github.com) | deb-get: add page (#8172) | 2022-07-09T19:00:00 | [5384a4f3a043](https://github.com/tldr-pages/tldr/commit/5384a4f3a0431f666a2d338a0496bbdd0fa8986f)

