---
author: ['Marco Bonelli']
date: 1570281951
title: "exa"
description: "exa, Un moderno sostituto per `ls` (elenca i contenuti di una directory)."
categories: "common"
---
> Maggiori informazioni: <https://the.exa.website>.

- Elenca i file nella directory corrente, uno per riga:

```bash
exa --oneline
```

- Elenca tutti i file, inclusi quelli nascosti:

```bash
exa --all
```

- Elenca tutti i file e mostra informazioni (permessi, dimensione e data di ultima modifica):

```bash
exa --long --all
```

- Elenca i file, ordinandoli per dimensione decrescente:

```bash
exa --reverse --sort=size
```

- Mostra un albero dei file con 3 livelli di profondità:

```bash
exa --long --tree --level=3
```

- Elenca i file e mostra informazioni, ordinandoli per ultima modifica (più vechci prima):

```bash
exa --long --sort=modified
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | exa: add Italian translation. | 2019-10-05T15:25:51 | [8b4a06f09bc7](https://github.com/tldr-pages/tldr/commit/8b4a06f09bc734b7a662318ec9f4363856204366)

