---
author: ['Lucas Gabriel Schneider', 'Andrea']
date: 1629110041
title: "modinfo, TLDR Pages"
description: "modinfo, Estrae le informazioni riguardarti un modulo del kernel Linux."
categories: "linux"
---
> Maggiori informazioni: <https://manned.org/modinfo>.

- Elenca tutti gli attributi di un modulo del kernel:

```bash
modinfo modulo_del_kernel
```

- Elenca solamente gli attributi specificati:

```bash
modinfo -F author|description|license|parm|filename modulo_del_kernel
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Andrea](mailto:agnophi@gmail.com) | acpi, adduser, cp, fsck, halt, lsmod, lsusb, mkfs, modinfo, modprobe, pidof, poweroff: add Italian translation | 2020-10-28T18:59:18 | [78a1f4ce6b47](https://github.com/tldr-pages/tldr/commit/78a1f4ce6b4737c3049ec89305ab9a6f1ba54601)

