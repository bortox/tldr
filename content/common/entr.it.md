---
author: ['Marco Bonelli', 'marchersimon']
date: 1618869951
title: "entr"
description: "entr, Esegui comandi arbitrari al cambiamento di file."
categories: "common"
---
> Maggiori informazioni: <https://manned.org/entr>.

- Ricompila con `make` se qualsiasi file in quasiasi sottodirectory cambia:

```bash
ag -l | entr make
```

- Ricompila e testa con `make` se qualsiasi file sorgente `.c` nella cartella corrente cambia:

```bash
ls *.c | entr 'make && make test'
```

- Invia il segnale `SIGTERM` ad un sottoprocesso ruby precedentemente avviato prima di eseguire `ruby main.rb`:

```bash
ls *.rb | entr -r ruby main.rb
```

- Esegui un comando con il file cambiato (`/_`) come argomento:

```bash
ls *.sql | entr psql -f /_
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Marco Bonelli](mailto:marco@mebeim.net) | entr: add Italian translation. | 2019-10-05T15:25:51 | [07f270b4584a](https://github.com/tldr-pages/tldr/commit/07f270b4584a6cec64ceeebf05a2446af20c97b7)

