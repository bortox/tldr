---
author: ['Lucas Gabriel Schneider', 'Dario Vladović', 'Marco Bonelli', 'marchersimon']
date: 1634848494
title: "du, TLDR Pages"
description: "du, Utilizzo del disco: stima e riassumi lo spazio utilizzato da file e directory."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/du>.

- Elenca le dimensioni di una directory ed ogni sotto-directory, nell'unità specificata (B/KiB/MiB):

```bash
du -b|k|m percorso/alla/directory
```

- Elenca le dimensioni di una directory ed ogni sotto-directory, in formato umanamente leggibile (seleziona automaticamente l'unità appropriata per ogni dimensione):

```bash
du -h percorso/alla/directory
```

- Mostra la dimensione di una singola directory, in unità umanamente leggibili:

```bash
du -sh percorso/alla/directory
```

- Mostra in formato umanamente leggibile le dimensioni di una directory e tutti i file e directory in essa contenuti:

```bash
du -ah percorso/alla/directory
```

- Elenca le dimensioni umanamente leggibili di una directory e d ogni sotto-directory, fino ad N livelli di profondità:

```bash
du -h --max-depth=N percorso/alla/directory
```

- Mostra le dimensioni umanamente leggibili di tutti i file `.jpg` nelle sottocartelle della cartella corrente, e mostra il totale cumulativo alla fine:

```bash
du -ch */*.jpg
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | du: fix wrong byte units (#7131) | 2021-10-21T22:34:54 | [0ddea62ffb82](https://github.com/tldr-pages/tldr/commit/0ddea62ffb822afabf0437c9a0d15258f13ce672)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | du: add more information link (#5605) | 2021-03-30T15:55:04 | [5ba367c2dd90](https://github.com/tldr-pages/tldr/commit/5ba367c2dd907bb693651c017f68ce0ee42ca3f1)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | du: add Italian translation. | 2019-10-05T15:25:51 | [d10c44d8284c](https://github.com/tldr-pages/tldr/commit/d10c44d8284cf7e45bd605b6f682ea55e99d18b3)

