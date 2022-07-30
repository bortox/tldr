---
author: ['Lucas Gabriel Schneider', 'Marco Bonelli']
date: 1612112718
title: "cppclean"
description: "cppclean, Trova codice inutilizzato in progetti C++."
categories: "common"
---
> Maggiori informazioni: <https://github.com/myint/cppclean>.

- Esegui nella directory di un progetto:

```bash
cppclean percorso/a/directory_progetto
```

- Esegui su di un progetto dove gli header sono nella directory "inc1" ed "inc2":

```bash
cppclean percorso/a/directory_progetto --include-path=inc1 --include-path=inc2
```

- Esegui su di uno specifico file `main.cpp`:

```bash
cppclean main.cpp
```

- Esegui della directory corrente, escludendo la directory "build":

```bash
cppclean . --exclude=build
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | cppclean: add Italian translation. | 2019-06-10T01:35:02 | [0d300866c11e](https://github.com/tldr-pages/tldr/commit/0d300866c11e36399466b27317605b12dcd05acd)

