---
author: ['Ali Malek']
date: 1570967348
title: "ceph"
description: "ceph, A unified storage system."
categories: "linux"
---
> More information: <https://ceph.io>.

- Check cluster health status:

```bash
ceph status
```

- Check cluster usage stats:

```bash
ceph df
```

- Get the statistics for the placement groups in a cluster:

```bash
ceph pg dump --format plain
```

- Create a storage pool:

```bash
ceph osd pool create pool_name page_number
```

- Delete a storage pool:

```bash
ceph osd pool delete pool_name
```

- Rename a storage pool:

```bash
ceph osd pool rename current_name new_name
```

- Self-repair pool storage:

```bash
ceph pg repair pool_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ali Malek](mailto:ali.malek.71@gmail.com) | ceph: add page (#3351) | 2019-10-13T13:49:08 | [fdbacd900de4](https://github.com/tldr-pages/tldr/commit/fdbacd900de49b44045ba0977af482c2c54a4626)

