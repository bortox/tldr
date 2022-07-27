---
author: ['Marco Bonelli', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "chown, TLDR Pages"
description: "chown, Cambia utente e gruppo proprietario di file e directory."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/chown>.

- Cambia l'utente proprietario di un file/directory:

```bash
chown utente percorso/a/file_o_directory
```

- Cambia utente e gruppo proprietari di un file/directory:

```bash
chown utente:gruppo percorso/a/file_o_directory
```

- Cambia ricorsivamente il proprietario di una cartella ed i suoi contenuti:

```bash
chown -R utente percorso/alla/directory
```

- Cambia il proprietario di un link simbolico:

```bash
chown -h utente percorso/al/link_simbolico
```

- Cambia il proprietario di un file/directory rendendolo uguale a quello di un altro file di riferimento:

```bash
chown --reference=percorso/al/file_riferimento percorso/a/file_o_directory
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chown: add more information link (#5555) | 2021-03-30T15:29:42 | [8d147522d127](https://github.com/tldr-pages/tldr/commit/8d147522d127f65aca087b791bf2deb46a43f59d)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | chown: add Italian translation. | 2019-03-03T23:44:18 | [49153f790178](https://github.com/tldr-pages/tldr/commit/49153f790178610b3f5b3272a08e077eeae578ba)

