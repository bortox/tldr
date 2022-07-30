---
author: ['Marco Bonelli']
date: 1560123302
title: "cppcheck"
description: "cppcheck, Strumento di analisi statica per codice C/C++."
categories: "common"
---
> Piuttosto che sugli errori di sintassi, si concentra su tipi di bug che normalmente non vengono rilevati dai compilatori.

> Maggiori informazioni: <http://cppcheck.sourceforge.net>.

- Controlla la directory corrente ricorsivamente, mostrando il progresso a schermo e loggando i messaggi di errore in un file:

```bash
cppcheck . 2> cppcheck.log
```

- Controlla una determinata directory ricorsivamente, senza stampare informazioni sul progresso:

```bash
cppcheck --quiet path/to/directory
```

- Controlla un determinato file, specificando quali test eseguire (di default, solo gli errori sono mostrati):

```bash
cppcheck --enable=error|warning|style|performance|portability|information|all percorso/al/file.cpp
```

- Elenca i test disponibili:

```bash
cppcheck --errorlist
```

- Controlla un determinato file, ignorando specifici test:

```bash
cppcheck --suppress=id_test1 --suppress=it_test2 percorso/al/file.cpp
```

- Controlla la directory corrente, fornendo percorsi da includere per file esterni (e.g. librerie esterne):

```bash
cppcheck -I include/directory_1 -I include/directory_2 .
```

- Controlla un progetto Microsoft Visual Studio (`*.vcxproj`) o file solution (`*.sln`):

```bash
cppcheck --project=path/to/progetto.sln
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | cppcheck: add Italian translation. | 2019-06-10T01:35:02 | [91960d0abb88](https://github.com/tldr-pages/tldr/commit/91960d0abb88957e482c466ed5a9928de9e2a2e7)

