---
author: ['Marco Bonelli']
date: 1570281951
title: "emacsclient, TLDR Pages"
description: "emacsclient, Apri file in un server emacs esistente."
categories: "common"
---
> Maggiori informazioni: <https://www.emacswiki.org/emacs/EmacsClient>.

- Apri un file in un server Emacs esistene (utilizzando la GUI se disponibile):

```bash
emacsclient nome_file
```

- Apri un file in modalità console (senza finestra X):

```bash
emacsclient -nw nome_file
```

- Apri un file in un frame Emacs esistente e ritorna immediatamente:

```bash
emacsclient -n nome_file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | emacsclient: add Italian translation. | 2019-10-05T15:25:51 | [7149c32b0932](https://github.com/tldr-pages/tldr/commit/7149c32b093206e89d1397ed456ec7f59c5b46d0)

