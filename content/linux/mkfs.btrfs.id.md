---
author: ['Azrael JD']
date: 1641795505
title: "mkfs.btrfs, TLDR Pages"
description: "mkfs.btrfs, Membuat sistem file btrfs."
categories: "linux"
---
> Default ke `raid1`, yang menyatakan 2 salinan sebuah blok data disebar ke 2 perangkat yang berbeda.

> Informasi lebih lanjut: <https://btrfs.wiki.kernel.org/index.php/Manpage/mkfs.btrfs>.

- Membuat sebuah sistem file btrfs di satu perangkat:

```bash
sudo mkfs.btrfs --metadata single --data single /dev/sda
```

- Membuat sebuah sistem file btrfs di beberapa perangkat dengan raid1:

```bash
sudo mkfs.btrfs --metadata raid1 --data raid1 /dev/sda /dev/sdb /dev/sdN
```

- Mengatur sebuah label untuk sistem file:

```bash
sudo mkfs.btrfs --label "label" /dev/sda [/dev/sdN]
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | mkfs.btrfs: add Indonesian translation (#7632) | 2022-01-10T07:18:25 | [5f24ccbc17ee](https://github.com/tldr-pages/tldr/commit/5f24ccbc17ee3d09ac3f02b2780a5915b301aef0)

