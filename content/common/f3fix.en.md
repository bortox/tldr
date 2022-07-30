---
author: ['Zlatan Vasović', 'Starbeamrainbowlabs']
date: 1580730823
title: "f3fix"
description: "f3fix, Edit the partition table of a fake flash drive."
categories: "common"
---
> See also `f3probe`, `f3write`, `f3read`.

> More information: <http://oss.digirati.com.br/f3/>.

- Fill a fake flash drive with a single partition that matches its real capacity:

```bash
sudo f3fix /dev/device_name
```

- Mark the partition as bootable:

```bash
sudo f3fix --boot /dev/device_name
```

- Specify the filesystem:

```bash
sudo f3fix --fs-type=filesystem_type /dev/device_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | Make tldr-bot happy | 2020-02-03T12:53:43 | [972359f339cf](https://github.com/tldr-pages/tldr/commit/972359f339cf6ff0fb7c03ef3564a9cc58684d5d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | f3fix: add page | 2020-02-03T12:53:43 | [1f51696e8351](https://github.com/tldr-pages/tldr/commit/1f51696e83511711a761506543e52794af8c72ea)

