---
author: ['marchersimon']
date: 1659887060
title: "tlmgr restore"
description: "tlmgr restore, Restore package backups created with `tlmgr backup`."
categories: "common"
---
> The default backup directory is specified by the `backupdir` option, and can be obtained with `tlmgr option`.

> More information: <https://www.tug.org/texlive/tlmgr.html>.

- List all available backup revisions for all packages:

```bash
tlmgr restore
```

- List all available backup revisions for a specific package:

```bash
tlmgr restore package
```

- Restore a specific revision of a specific package:

```bash
tlmgr restore package revision
```

- Restore the latest revision of all backed-up packages:

```bash
tlmgr restore --all
```

- Restore a package from a custom backup directory:

```bash
tlmgr restore package revision --backupdir path/to/backup_directory
```

- Perform a dry-run and print all taken actions without making them:

```bash
tlmgr restore --dry-run package revision
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-restore: add page (#8288) | 2022-08-07T17:44:20 | [91099b4874ba](https://github.com/tldr-pages/tldr/commit/91099b4874ba61fd085fc3fbd1a9deda73fdee27)

