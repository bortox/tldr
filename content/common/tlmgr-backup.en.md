---
author: ['CleanMachine1', 'marchersimon']
date: 1656619054
title: "tlmgr backup"
description: "tlmgr backup, Manage backups of TeX Live packages."
categories: "common"
---
> The default backup location is saved in the `backupdir` setting, which can be obtained with `tlmgr option`.

> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Make a backup of one or more packages:

```bash
tlmgr backup package1 package2 ...
```

- Make a backup of all packages:

```bash
tlmgr backup --all
```

- Make a backup to a specific directory:

```bash
tlmgr backup package --backupdir path/to/backup_directory
```

- Remove a backup of one or more packages:

```bash
tlmgr backup clean package1 package2 ...
```

- Remove all backups:

```bash
tlmgr backup clean --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Fix spelling mistakes | 2022-06-30T21:57:34 | [a0828299099a](https://github.com/tldr-pages/tldr/commit/a0828299099a2224eca625dcf412c341124c5011)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-backup: add page (#6581) | 2021-09-24T01:34:07 | [96bef1951ca7](https://github.com/tldr-pages/tldr/commit/96bef1951ca7e6ceabb88e487132fd68d2f2e2cc)

