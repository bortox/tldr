---
author: ['Gingka Akiyama', 'Seth Falco', 'Emily Grace Seville']
date: 1644837703
title: "tmutil, TLDR Pages"
description: "tmutil, Utility for managing Time Machine backups. Most verbs require root privileges."
categories: "osx"
---
> More information: <https://ss64.com/osx/tmutil.html>.

- Set an HFS+ drive as the backup destination:

```bash
sudo tmutil setdestination path/to/disk_mount_point
```

- Set an APF share or SMB share as the backup destination:

```bash
sudo tmutil setdestination "protocol://user[:password]@host/share"
```

- Append the given destination to the list of destinations:

```bash
sudo tmutil setdestination -a destination
```

- Enable automatic backups:

```bash
sudo tmutil enable
```

- Disable automatic backups:

```bash
sudo tmutil disable
```

- Start a backup, if one is not running already, and release control of the shell:

```bash
sudo tmutil startbackup
```

- Start a backup and block until the backup is finished:

```bash
sudo tmutil startbackup -b
```

- Stop a backup:

```bash
sudo tmutil stopbackup
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Gingka Akiyama](mailto:33764485+GingkathFox@users.noreply.github.com) | tmutil: add page (#5054) | 2020-12-29T12:43:22 | [223e095d7d10](https://github.com/tldr-pages/tldr/commit/223e095d7d1034bc5de9c86698b633d4904d9446)

