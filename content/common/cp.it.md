---
author: ['gRastello', 'Dario Vladović', 'bl-ue', 'marchersimon']
date: 1617493464
title: "cp, TLDR Pages"
description: "cp, Copia file e directory."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/cp>.

- Copia un file in un'altra posizione:

```bash
cp percorso/al/file percorso/alla/copia
```

- Copia un file in una directory mantenendo il nome:

```bash
cp percorso/al/file percorso/alla/directory
```

- Copia una directory ricorsivamente in un'altra posizione:

```bash
cp -r percorso/alla/directory percorso/alla/copia
```

- Copia una directory ricorsivamente in modo verboso (mostra a schermo ogni file copiato):

```bash
cp -vr percorso/alla/directory percorso/alla/copia
```

- Copia i contenuti di una directory in una seconda directory:

```bash
cp -r percorso/alla/directory/* percorso/alla/seconda/directory
```

- Copia tutti i file di testo in una seconda directory in modo interattivo (chiede conferma prima di sovrascrivere):

```bash
cp -i *.txt percorso/alla/directory
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cp: add more information link (#5556) | 2021-03-30T12:30:03 | [ad46ebe87a57](https://github.com/tldr-pages/tldr/commit/ad46ebe87a578bcb5e61d26addcf1bdfe287d75f)
[gRastello](mailto:gabriele.rastello@edu.unito.it) | cp: add Italian translation. fixed typos added missing period | 2019-02-06T17:08:07 | [e6089c1e76fe](https://github.com/tldr-pages/tldr/commit/e6089c1e76fe3ee968f004b01943cd5fe202181f)

