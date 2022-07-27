---
author: ['Jimmy', 'Lucas Gabriel Schneider', 'mxmxyz']
date: 1633450842
title: "mount, TLDR Pages"
description: "mount, Fornisce accesso a un intero filesystem in una cartella specifica."
categories: "common"
---
> Maggiori informazioni: <https://manned.org/mount.8>.

- Mostra tutti i filesystem montati:

```bash
mount
```

- Monta un dispositivo in una cartella:

```bash
mount -t tipo_di_filesystem percorso/al/dispositivo percorso/alla/cartella_desiderata
```

- Monta un CD-ROM (con il filetypo ISO9660) a `/cdrom` (sola lettura):

```bash
mount -t iso9660 -o ro /dev/cdrom /cdrom
```

- Monta tutti i filesystem definiti in `/etc/fstab`:

```bash
mount -a
```

- Monta un filesystem specifico descritto in `/etc/fstab` (ad esempio `/dev/sda1 /my_drive ext2 defaults 0 2`):

```bash
mount /my_drive
```

- Monta una cartella in un'altra cartella:

```bash
mount --bind percorso/alla/vecchia_cartella percorso/alla/nuova_cartella
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Jimmy](mailto:30603522+jim4067@users.noreply.github.com) | mount: add more information link (#6788) | 2021-10-05T18:20:42 | [96bb5fde4169](https://github.com/tldr-pages/tldr/commit/96bb5fde416932e736be172e2de8be432596aaee)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[mxmxyz](mailto:mxmxyzgxyzt@gmail.com) | 6 translations to italian | 2020-09-09T02:42:53 | [ae3ba00236f1](https://github.com/tldr-pages/tldr/commit/ae3ba00236f1e305ae16d0a317d345bffe88c857)

