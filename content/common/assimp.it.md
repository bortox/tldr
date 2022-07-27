---
author: ['Marco Bonelli', 'Schneider']
date: 1559564381
title: "assimp, TLDR Pages"
description: "assimp, Client da linea di comando per la Open Asset Import Library."
categories: "common"
---
> Supporta il caricamento di 40+ formati di file per modelli 3D, e l'espoerazione di diversi formati 3D popolari.

> Maggiori informazioni: <http://www.assimp.org/>.

- Elenca tutti i formati supportati:

```bash
assimp listext
```

- Elenca tutti i formati supportati per l'esportazione:

```bash
assimp listexport
```

- Converti un file a uno dei tipi supportati, utilizzando i parametri predefiniti:

```bash
assimp export file_input.stl file_output.obj
```

- Converti un file utilizzando parametri personalizzati (il file dox_cmd.h nel source code di assimp contiene una lista di parametri disponibili):

```bash
assimp export file_input.stl file_output.obj parametri
```

- Mostra un riepilogo del contenuto di un file:

```bash
assimp info percordo/al/file
```

- Elenca tutti i sottocomandi disponibili (detti "verbs"):

```bash
assimp help
```

- Chiedi aiuto per uno specifico sottocomando (ad esempio riguardo i suoi parametri):

```bash
assimp sottocomando --help
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\assimp.md: add homepage | 2019-05-14T19:40:23 | [2ea4606a1869](https://github.com/tldr-pages/tldr/commit/2ea4606a18692adf4ed892a4c649ffca5ab5a9c3)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | assimp: add Italian translation. | 2019-01-28T19:10:19 | [3ee5d48bc9af](https://github.com/tldr-pages/tldr/commit/3ee5d48bc9af9020bf800feb0bd333cf4563eab8)

