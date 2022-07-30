---
author: ['Aakash Sharma']
date: 1631895419
title: "aura"
description: "aura, The Aura Package Manager: A secure, multilingual package manager for Arch Linux and the AUR."
categories: "linux"
---
> More information: <https://github.com/fosskers/aura>.

- Search for packages from the official repositories and AUR:

```bash
aura --aursync --both --search package_name|search_regex
```

- Install a package from the AUR:

```bash
aura --aursync package_name
```

- Update all AUR packages in a verbose mode and remove all make dependencies:

```bash
aura --aursync --diff --sysupgrade --delmakedeps --unsuppress
```

- Install a package from the official repositories:

```bash
aura --sync package_name
```

- Synchronize and update all packages from the official repositories:

```bash
aura --sync --refresh --sysupgrade
```

- Downgrade a package using the package cache:

```bash
aura --downgrade package_name
```

- Remove a package and its dependencies:

```bash
aura --remove --recursive --unneeded package_name
```

- Remove orphan packages (installed as dependencies but not required by any package):

```bash
aura --orphans --abandon
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Aakash Sharma](mailto:60808802+AakashSharma7269@users.noreply.github.com) | aura: add page (#6533) | 2021-09-17T18:16:59 | [8fa913a32bc9](https://github.com/tldr-pages/tldr/commit/8fa913a32bc9628c7feb9ed1496c8711c3301542)

