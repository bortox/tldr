---
author: ['flyxyz123', 'Andrea']
date: 1634418287
title: "pidof, TLDR Pages"
description: "pidof, Ottiene l'ID di un processo a partire dal suo nome."
categories: "linux"
---
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
[flyxyz123](mailto:30398651+flyxyz123@users.noreply.github.com) | pidof: fix bug in kill example (#6953) | 2021-10-16T23:04:47 | [d8efc478c7e6](https://github.com/tldr-pages/tldr/commit/d8efc478c7e6835c9ce70419307349d5a6118afd)
[Andrea](mailto:agnophi@gmail.com) | acpi, adduser, cp, fsck, halt, lsmod, lsusb, mkfs, modinfo, modprobe, pidof, poweroff: add Italian translation | 2020-10-28T18:59:18 | [78a1f4ce6b47](https://github.com/tldr-pages/tldr/commit/78a1f4ce6b4737c3049ec89305ab9a6f1ba54601)

