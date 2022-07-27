---
author: ['Ein Verne']
date: 1634040199
title: "duplicacy, TLDR Pages"
description: "duplicacy, A lock-free deduplication cloud backup tool."
categories: "common"
---
> More information: <https://github.com/gilbertchen/duplicacy/wiki>.

- Use current directory as the repository, initialize a SFTP storage and encrypt the storage with a password:

```bash
duplicacy init -e snapshot_id sftp://user@192.168.2.100/path/to/storage/
```

- Save a snapshot of the repository to the default storage:

```bash
duplicacy backup
```

- List snapshots of current repository:

```bash
duplicacy list
```

- Restore the repository to a previously saved snapshot:

```bash
duplicacy restore -r revision
```

- Check the integrity of snapshots:

```bash
duplicacy check
```

- Add another storage to be used for the existing repository:

```bash
duplicacy add storage_name snapshot_id storage_url
```

- Prune a specific revision of snapshot:

```bash
duplicacy prune -r revision
```

- Prune revisions, keeping one revision every `n` days for all revisions older than `m` days:

```bash
duplicacy prune -keep n:m
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | duplicacy: add page (#6598) | 2021-10-12T14:03:19 | [8ea6aab9ef58](https://github.com/tldr-pages/tldr/commit/8ea6aab9ef588a8fc917966a280e968ff5413c54)

