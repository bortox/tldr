---
author: ['gsobell', 'Axel Navarro']
date: 1630697779
title: "md5sum, TLDR Pages"
description: "md5sum, Calcola i checksum crittografici di tipo MD5."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/md5sum>.

- Calcolare il checksum MD5 di un file:

```bash
md5sum percorso/al/file
```

- Calcola i checksum MD5 per più di un file:

```bash
md5sum percorso/al/file1 percorso/al/file2
```

- Verifica che tutti i file abbiano checksum corrispondenti al file di MD5SUM:

```bash
md5sum -c percorso/al/file.md5
```

- Calcola il checksum MD5 dal standard input:

```bash
echo "testo" | md5sum
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | md5sum: replace filename by path/to/file (#6465) | 2021-09-03T21:36:19 | [4887b989c62a](https://github.com/tldr-pages/tldr/commit/4887b989c62afb82c203695729f98f0c70af132a)
[gsobell](mailto:82414189+gsobell@users.noreply.github.com) | cmatrix, md5sum, more: add Italian translation (#6211) | 2021-07-11T20:26:41 | [001cc048e3e2](https://github.com/tldr-pages/tldr/commit/001cc048e3e26e2e5535db671d58344f0b77bec8)

