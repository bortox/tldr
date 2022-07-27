---
author: ['Lucas Gabriel Schneider', 'Andrea']
date: 1629110041
title: "lsusb, TLDR Pages"
description: "lsusb, Visualizza le informazioni su i bus USB e i dispositivi a loro connessi."
categories: "linux"
---
> Maggiori informazioni: <https://manned.org/lsusb>.

- Elenca tutti i dispositivi USB disponibili:

```bash
lsusb
```

- Visualizza la gerarchia USB come un albero:

```bash
lsusb -t
```

- Elenca informazioni prolisse riguardo ai dispositivi USB:

```bash
lsusb --verbose
```

- Elenca informazioni dettagliate riguardo ad un dispositivo USB:

```bash
lsusb -D dispositivo
```

- Elenca solamente i dispositivi con un certo id fornitore e id prodotto:

```bash
lsusb -d fornitore:prodotto
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Andrea](mailto:agnophi@gmail.com) | acpi, adduser, cp, fsck, halt, lsmod, lsusb, mkfs, modinfo, modprobe, pidof, poweroff: add Italian translation | 2020-10-28T18:59:18 | [78a1f4ce6b47](https://github.com/tldr-pages/tldr/commit/78a1f4ce6b4737c3049ec89305ab9a6f1ba54601)

