---
author: ['MT']
date: 1581557028
title: "findfs"
description: "findfs, Finds a filesystem by label or UUID."
categories: "linux"
---
> More information: <https://mirrors.edge.kernel.org/pub/linux/utils/util-linux>.

- Search block devices by filesystem label:

```bash
findfs LABEL=label
```

- Search by filesystem UUID:

```bash
findfs UUID=uuid
```

- Search by partition label (GPT or MAC partition table):

```bash
findfs PARTLABEL=partition_label
```

- Search by partition UUID (GPT partition table only):

```bash
findfs PARTUUID=partition_uuid
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[MT](mailto:59728838+mt-empty@users.noreply.github.com) | findfs: add page (#3850) | 2020-02-13T02:23:48 | [a0f11588eb3e](https://github.com/tldr-pages/tldr/commit/a0f11588eb3e2bc9b634f4fd7822078e2c97f48d)

