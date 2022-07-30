---
author: ['Axel Navarro']
date: 1627405588
title: "synopkg"
description: "synopkg, Package management utility for Synology DiskStation Manager."
categories: "linux"
---
> More information: <https://www.synology.com/dsm>.

- List the names of installed packages:

```bash
synopkg list --name
```

- List packages which depend on a specific package:

```bash
synopkg list --depend-on package
```

- Start/Stop a package:

```bash
sudo synopkg start|stop package
```

- Print the status of a package:

```bash
synopkg status package
```

- Uninstall a package:

```bash
sudo synopkg uninstall package
```

- Check if updates are available for a package:

```bash
synopkg checkupdate package
```

- Upgrade all packages to the latest version:

```bash
sudo synopkg upgradeall
```

- Install a package from a synopkg file:

```bash
sudo synopkg install path/to/package.spk
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | synopkg: add page (#6264) | 2021-07-27T19:06:28 | [1f42eaac025f](https://github.com/tldr-pages/tldr/commit/1f42eaac025f32f80bfb472be1e8138025afff6c)

