---
author: ['Marco Bonelli']
date: 1560123302
title: "cpio"
description: "cpio, Copia file da/a archivi."
categories: "common"
---
> Supporta i seguenti formati di archivio: cpio binario, vecchio ASCII, nuovo ASCII, crc, HPUX binario, HPUX vecchio ASCII, vecchio tar, e tar POSIX.1.

> Maggiori informazioni: <https://www.gnu.org/software/cpio>.

- Accetta una lista di nomi di file da standard input ed aggiungili ad un archivio in formato binario cpio:

```bash
echo "file1 file2 file3" | cpio -o > archivio.cpio
```

- Copia tutti i file e le directory in una directory ed aggiungili ad un archivio, in modalità verbosa:

```bash
find path/to/directory | cpio -ov > archivio.cpio
```

- Estrai file da un archivio, generando le directory necessarie, in modalità verbosa:

```bash
cpio -idv < archivio.cpio
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | cpio: add Italian translation. | 2019-06-10T01:35:02 | [b74ce1071f84](https://github.com/tldr-pages/tldr/commit/b74ce1071f84cafde6d06eeb72f25f9a5a9332a7)

