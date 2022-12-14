---
author: ['Andrea', 'marchersimon']
date: 1633112881
title: "mkfs"
description: "mkfs, Costruisce un filesystem Linux su una partizione del disco rigido."
categories: "linux"
---
> Questo comando è deprecato in favore degli strumenti specifici per filesystem: mkfs.tipo.

> Maggiori informazioni: <https://manned.org/mkfs>.

- Costruisce un filesystem Linux ext2 su una partizione:

```bash
mkfs percorso/alla/partizione
```

- Costruisce un filesystem del tipo specificato:

```bash
mkfs -t ext4 percorso/alla/partizione
```

- Costruisce un filesystem del specificato e controlla la presenza di settori danneggiati:

```bash
mkfs -c -t ntfs percorso/alla/partizione
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Andrea](mailto:agnophi@gmail.com) | acpi, adduser, cp, fsck, halt, lsmod, lsusb, mkfs, modinfo, modprobe, pidof, poweroff: add Italian translation | 2020-10-28T18:59:18 | [78a1f4ce6b47](https://github.com/tldr-pages/tldr/commit/78a1f4ce6b4737c3049ec89305ab9a6f1ba54601)

