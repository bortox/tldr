---
author: ['Marco Bonelli', 'marchersimon']
date: 1620637392
title: "ag, TLDR Pages"
description: "ag, The Silver Searcher. Come `ack`, ma più veloce."
categories: "common"
---
> Maggiori informazioni: <https://github.com/ggreer/the_silver_searcher>.

- Trova file contenenti "foo" e mostra le corrisponenti linee contenenti il termine:

```bash
ag foo
```

- Trova file contenenti "foo" in una specifica directory:

```bash
ag foo percorso/alla/directory
```

- Trova file contenenti "foo" elencandone solamente i nomi:

```bash
ag -l foo
```

- Trova file contenenti "FOO" senza distinguere tra maiuscole e minuscole, e stampa solo il termine trovato piuttosto che l'intera linea:

```bash
ag -i -o FOO
```

- Trova "foo" in file il quale nome contiene "bar":

```bash
ag foo -G bar
```

- Trova file il quale contenuto soddisfi una determinata espressione regolare:

```bash
ag 'espressione_regolare'
```

- Trova file il quale nome contiene "foo":

```bash
ag -g foo
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: add italian translations (#2692) Translated 13 pages into italian: 7z 7za 7zr ab abduco ack adb ag airpaste alias [...] | 2019-01-11T01:34:17 | [1286509fe557](https://github.com/tldr-pages/tldr/commit/1286509fe557aaa701a1ebe07ce0c5c0b7ef6959)

