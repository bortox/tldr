---
author: ['Azrael JD']
date: 1641708105
title: "mkfs.ext4, TLDR Pages"
description: "mkfs.ext4, Membuat sistem file ext4 didalam sebuah partisi."
categories: "linux"
---
> Informasi lebih lanjut: <https://manned.org/mkfs.ext4>.

- Membuat sistem file ext4 di dalam partisi 1 di perangkat B (`sdb1`):

```bash
sudo mkfs.ext4 /dev/sdb1
```

- Membuat sistem file ext4 dengan label volume:

```bash
sudo mkfs.ext4 -L label_volume /dev/sdb1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | mkfs.ext4: add Indonesian translation (#7623) | 2022-01-09T07:01:45 | [318b5aae9111](https://github.com/tldr-pages/tldr/commit/318b5aae9111e9241c6ef773c1646f256bb388ef)

