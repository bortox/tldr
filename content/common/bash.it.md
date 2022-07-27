---
author: ['Marco Bonelli', 'marchersimon']
date: 1633112881
title: "bash, TLDR Pages"
description: "bash, Bourne-Again SHell."
categories: "common"
---
> Interprete da linea di comando compatibile con `sh`.

> Maggiori informazioni: <https://gnu.org/software/bash/>.

- Avvia una shell interattiva:

```bash
bash
```

- Esegui un comando:

```bash
bash -c "comando"
```

- Esegui dei comandi da un file:

```bash
bash file.sh
```

- Esegui dei comandi da un file, loggando tutti i comandi eseguiti nel terminale:

```bash
bash -x file.sh
```

- Esegui comandi da standard input:

```bash
bash -s
```

- Stampa informazioni sulla versione di bash (usa `echo $BASH_VERSION` per mostrare solo la versione):

```bash
bash --version
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | bash: add Italian translation. | 2019-01-28T19:10:19 | [0d2793a34074](https://github.com/tldr-pages/tldr/commit/0d2793a34074e317d5b7cd769e55e7a3e62e6835)

