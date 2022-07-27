---
author: ['Marco Bonelli']
date: 1560123302
title: "ctest, TLDR Pages"
description: "ctest, Programma per eseguire test in progetti CMake."
categories: "common"
---
> Maggiori informazioni: <https://gitlab.kitware.com/cmake/community/wikis/doc/ctest/Testing-With-CTest>.

- Esegui tutti i test definiti nel progetto CMakw, eseguendo 4 job allo stesso tempo in parallelo:

```bash
ctest -j4 --output-on-failure
```

- Mostra una lista dei test disponibili:

```bash
ctest -N
```

- Esegui un singolo test in base al suo nome, o filtrando con una espressione regolare:

```bash
ctest --output-on-failure -R '^nome_test$'
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | ctest: add Italian translation. | 2019-06-10T01:35:02 | [69001bb99576](https://github.com/tldr-pages/tldr/commit/69001bb99576231f7aebd8d7ab7e3aa0ab03cce4)

