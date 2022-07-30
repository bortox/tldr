---
author: ['Marco Bonelli']
date: 1578698516
title: "git clone"
description: "git clone, Clona un repository esistente."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-clone>.

- Clona un repository remoto esistente:

```bash
git clone url_repository_remoto
```

- Clona un repository remoto insieme ai suoi sottomoduli:

```bash
git clone --recursive url_repository_remoto
```

- Clona un repository locale:

```bash
git clone -l percorso/a/repository/locale
```

- Clona in modalità silenziosa:

```bash
git clone -q url_repository_remoto
```

- Clona un repository remoto scaricando solo i 10 commit più recenti del ramo principale (utile per risparmiare tempo):

```bash
git clone --depth 10 url_repository_remoto
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | git-clone: add Italian translation. Co-authored-by: Guido Lena Cota <guido.lenacota@kreuzwerker.de> | 2020-01-11T00:21:56 | [1539dee8c36c](https://github.com/tldr-pages/tldr/commit/1539dee8c36c955a507b2381430c76d421412fed)

