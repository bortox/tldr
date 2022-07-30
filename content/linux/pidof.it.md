---
author: ['flyxyz123', 'Andrea', 'marchersimon']
date: 1659075216
title: "pidof"
description: "pidof, Ottiene l'ID di un processo a partire dal suo nome."
categories: "linux"
---
> Maggiori informazioni: <https://manned.org/pidof>.

- Elenca gli ID di tutti i processi con un dato nome:

```bash
pidof bash
```

- Elenca un solo ID di processo con il nome specificato:

```bash
pidof -s bash
```

- Elenca gli ID dei processi con un dato includendo anche gli script:

```bash
pidof -x script.py
```

- Uccide tutti i processi con un dato nome:

```bash
kill $(pidof nome)
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[flyxyz123](mailto:30398651+flyxyz123@users.noreply.github.com) | pidof: fix bug in kill example (#6953) | 2021-10-16T23:04:47 | [d8efc478c7e6](https://github.com/tldr-pages/tldr/commit/d8efc478c7e6835c9ce70419307349d5a6118afd)
[Andrea](mailto:agnophi@gmail.com) | acpi, adduser, cp, fsck, halt, lsmod, lsusb, mkfs, modinfo, modprobe, pidof, poweroff: add Italian translation | 2020-10-28T18:59:18 | [78a1f4ce6b47](https://github.com/tldr-pages/tldr/commit/78a1f4ce6b4737c3049ec89305ab9a6f1ba54601)

