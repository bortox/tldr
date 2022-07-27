---
author: ['Andrea']
date: 1603907958
title: "acpi, TLDR Pages"
description: "acpi, Mostra lo stato e le informazioni termiche della batteria."
categories: "linux"
---
> Maggiori informazioni: <https://sourceforge.net/projects/acpiclient/files/acpiclient/>.

- Mostra le informazioni sulla batteria:

```bash
acpi
```

- Mostra le informazioni termiche:

```bash
acpi -t
```

- Mostra le informazioni sul dispositivo di raffreddamento:

```bash
acpi -c
```

- Mostra le informazioni termiche in gradi Fahrenheit:

```bash
acpi -tf
```

- Mostra tutte le informazioni:

```bash
acpi -V
```

- Estrae le informazioni da `/proc` invece che da `/sys`:

```bash
acpi -p
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Andrea](mailto:agnophi@gmail.com) | acpi, adduser, cp, fsck, halt, lsmod, lsusb, mkfs, modinfo, modprobe, pidof, poweroff: add Italian translation | 2020-10-28T18:59:18 | [78a1f4ce6b47](https://github.com/tldr-pages/tldr/commit/78a1f4ce6b4737c3049ec89305ab9a6f1ba54601)

