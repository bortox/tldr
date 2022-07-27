---
author: ['Stig124', 'Andrea']
date: 1625841955
title: "fsck, TLDR Pages"
description: "fsck, Controlla l'integrità di un filesystem o lo ripara. Il filesystem non dev'essere montato al momento in cui il comando viene eseguito."
categories: "linux"
---
> Maggiori informazioni: <https://manned.org/fsck>.

- Controlla il filesystem `/dev/sdX`, riportando eventuali blocchi danneggiati:

```bash
fsck /dev/sdX
```

- Controlla il filesystem `/dev/sdX`, riportando eventuali blocchi danneggiati e per ognuno consente all'utente di scegliere interattivamente se ripararlo:

```bash
fsck -r /dev/sdX
```

- Controlla il filesystem `/dev/sdX`, riportando eventuali blocchi danneggiati e riparandoli automaticamente:

```bash
fsck -a /dev/sdX
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Andrea](mailto:agnophi@gmail.com) | fsck: fix Italian translation | 2020-10-28T18:59:18 | [11f2e46358ca](https://github.com/tldr-pages/tldr/commit/11f2e46358ca2f158cd79546d0b0d79d1d628da2)
[Andrea](mailto:agnophi@gmail.com) | acpi, adduser, cp, fsck, halt, lsmod, lsusb, mkfs, modinfo, modprobe, pidof, poweroff: add Italian translation | 2020-10-28T18:59:18 | [78a1f4ce6b47](https://github.com/tldr-pages/tldr/commit/78a1f4ce6b4737c3049ec89305ab9a6f1ba54601)

