---
author: ['Marco Bonelli', 'Schneider', 'marchersimon']
date: 1633112881
title: "cmake, TLDR Pages"
description: "cmake, Generatore di ambienti di compilazione multipiattaforma."
categories: "common"
---
> Genera Makefile, progetti Visual Studio o altro, in base al sistema operativo.

> Maggiori informazioni: <https://cmake.org/cmake/help/latest/manual/cmake.1.html>.

- Genera un Makefile ed usalo per compilare un progetto nella stessa directory dei sorgenti:

```bash
cmake && make
```

- Genera un makefile ed usalo per compilare un progetto in una directory "build" separata (out-of-source build):

```bash
cmake -H. -Bbuild && make -C build
```

- Esegui cmake in modalità interattiva (chiederà i valori di ogni variabile invece di usare i predefiniti):

```bash
cmake -i
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\cmake.md: add homepage | 2019-05-14T19:40:23 | [c36c63034a88](https://github.com/tldr-pages/tldr/commit/c36c63034a88abc15186e8c2b1dd2d097c8c89ea)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | cmake: add Italian translation. | 2019-03-03T23:44:18 | [e11dac201be3](https://github.com/tldr-pages/tldr/commit/e11dac201be313e86e346e79ee261121f790221a)

