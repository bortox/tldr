---
author: ['Lucas Gabriel Schneider', 'Andrea']
date: 1629110041
title: "modprobe, TLDR Pages"
description: "modprobe, Aggiunge o rimuove moduli del kernel Linux."
categories: "linux"
---
> Maggiori informazioni: <https://manned.org/modprobe>.

- Fa finta di carica un modulo nel kernel, ma non lo fa veramente:

```bash
sudo modprobe --dry-run nome_del_modulo
```

- Carica un modulo nel kernel:

```bash
sudo modprobe nome_del_modulo
```

- Rimuove un modulo dal kernel:

```bash
sudo modprobe --remove nome_del_modulo
```

- Rimuove dal kernel un modulo e quelli che dipendono da quest'ultimo:

```bash
sudo modprobe --remove-dependencies nome_del_modulo
```

- Mostra le dipendenza di un modulo del kernel:

```bash
sudo modprobe --show-depends nome_del_modulo
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Andrea](mailto:agnophi@gmail.com) | acpi, adduser, cp, fsck, halt, lsmod, lsusb, mkfs, modinfo, modprobe, pidof, poweroff: add Italian translation | 2020-10-28T18:59:18 | [78a1f4ce6b47](https://github.com/tldr-pages/tldr/commit/78a1f4ce6b4737c3049ec89305ab9a6f1ba54601)

