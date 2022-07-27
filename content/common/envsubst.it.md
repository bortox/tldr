---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1618869951
title: "envsubst, TLDR Pages"
description: "envsubst, Sostituisci variabili di ambiente con il loro valore in stringhe di formato della shell."
categories: "common"
---
> Le variabili da sostituire devono essere nella forma `${var}` oppure `$var`.

> Maggiori informazioni: <https://www.gnu.org/software/gettext/manual/html_node/envsubst-Invocation.html>.

- Sostituisci variabili di ambiente in stdin e stampa l'output su stdout:

```bash
echo '$HOME' | envsubst
```

- Sostituisci variabili di ambiente in un file input e stampa l'output su stdout:

```bash
envsubst < percorso/a/file_input
```

- Sostituisci variabili di ambiente in un file input e scrivi l'output su un file:

```bash
envsubst < percorso/a/file_input > percorso/a/file_output
```

- Sostituisci in un file input le variabili di ambiente specificate in una lista separata da spazi:

```bash
envsubst $USER $HOME $SHELL < percorso/a/file_input
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | envsubst: add Italian translation. | 2019-10-05T15:25:51 | [810a5fceb67d](https://github.com/tldr-pages/tldr/commit/810a5fceb67d42f5b3be322d53f4793733fbdab7)

