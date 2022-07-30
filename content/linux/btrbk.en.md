---
author: ['Martin Matous']
date: 1652704341
title: "btrbk"
description: "btrbk, A tool for creating snapshots and remote backups of btrfs subvolumes."
categories: "linux"
---
> More information: <https://digint.ch/btrbk/doc/readme.html>.

- Print statistics about configured subvolumes and snapshots:

```bash
sudo btrbk stats
```

- List configured subvolumes and snapshots:

```bash
sudo btrbk list
```

- Print what would happen in a run without making the displayed changes:

```bash
sudo btrbk --verbose dryrun
```

- Run backup routines verbosely, show progress bar:

```bash
sudo btrbk --progress --verbose run
```

- Only create snapshots for configured subvolumes:

```bash
sudo btrbk snapshot
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Martin Matous](mailto:18654729+mmatous@users.noreply.github.com) | btrbk: add page (#7991) | 2022-05-16T14:32:21 | [fb4ab2c11e57](https://github.com/tldr-pages/tldr/commit/fb4ab2c11e571b7d117f303c06295a0734336086)

