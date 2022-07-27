---
author: ['danyeet']
date: 1618689672
title: "rusnapshot, TLDR Pages"
description: "rusnapshot, BTRFS snapshotting utility written in Rust."
categories: "linux"
---
> More information: <https://github.com/Edu4rdSHL/rusnapshot>.

- Create a snapshot using a config file:

```bash
sudo rusnapshot --config path/to/config.toml --cr
```

- List created snapshots:

```bash
sudo rusnapshot -c path/to/config.toml --list
```

- Delete a snapshot by ID or the name of the snapshot:

```bash
sudo rusnapshot -c path/to/config.toml --del --id snapshot_id
```

- Delete all `hourly` snapshots:

```bash
sudo rusnapshot -c path/to/config.toml --list --keep 0 --clean --kind hourly
```

- Create a read-write snapshot:

```bash
sudo rusnapshot -c path/to/config.toml --cr --rw
```

- Restore a snapshot:

```bash
sudo rusnapshot -c path/to/config.toml --id snapshot_id --restore
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[danyeet](mailto:dani65.dj@gmail.com) | rusnapshot: add page (#5776) | 2021-04-17T22:01:12 | [ea8ac0113302](https://github.com/tldr-pages/tldr/commit/ea8ac0113302c69e3a7ad79b70f9fbffbee5fa64)

