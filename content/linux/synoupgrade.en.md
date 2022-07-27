---
author: ['Axel Navarro']
date: 1627411914
title: "synoupgrade, TLDR Pages"
description: "synoupgrade, Upgrade a Synology DiskStation Manager (DSM) from the command-line."
categories: "linux"
---
> More information: <https://www.synology.com/dsm>.

- Check if upgrades are available:

```bash
sudo synoupgrade --check
```

- Check for patches without upgrading the DSM version:

```bash
sudo synoupgrade --check-smallupdate
```

- Download the latest upgrade available (use `--download-smallupdate` for patches):

```bash
sudo synoupgrade --download
```

- Start the upgrade process:

```bash
sudo synoupgrade --start
```

- Upgrade to the latest version automatically:

```bash
sudo synoupgrade --auto
```

- Apply patches without upgrading the DSM version automatically:

```bash
sudo synoupgrade --auto-smallupdate
```

- Upgrade the DSM using a patch file (should be an absolute path):

```bash
sudo synoupgrade --patch /path/to/file.pat
```

- Display help:

```bash
synoupgrade
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | synoupgrade: add page (#6262) | 2021-07-27T20:51:54 | [a14b29486630](https://github.com/tldr-pages/tldr/commit/a14b294866304ed89d76f30475b6a28b87d6a727)

