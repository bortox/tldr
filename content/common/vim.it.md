---
author: ['Marco Bonelli', 'mxmxyz', 'gRastello', 'marchersimon']
date: 1620637392
title: "vim"
description: "vim, Vi IMproved, un editor di testo per programmatori che fornisce diverse modalità per modificare testo."
categories: "common"
---
> Premi `i` per entrare in insert mode e `<Esc>` per tornare in normal mode dove non puoi inserire testo normalmente.

> Maggiori informazioni: <https://www.vim.org>.

- Apri un file in vim:

```bash
vim file
```

- Vai in insert mode (per inserire testo):

```bash
<Esc>i
```

- Copia ("yank") o taglia ("delete") la linea corrente (per incollarla poi con `P`):

```bash
<Esc>yy|dd
```

- Annulla l'ultima operazione:

```bash
<Esc>u
```

- Cerca un pattern nel file (usa `n`/`N` per spostarti al risultato successivo/precedente):

```bash
<Esc>/espressione_regolare<Invio>
```

- Effettua una sostituzione tramite espressione regolare nell'intero file:

```bash
<Esc>:%s/espressione_regolare/sostituzione/g<Invio>
```

- Salva modifiche al file ed esci:

```bash
<Esc>:wq<Invio>
```

- Esci senza salvare:

```bash
<Esc>:q!<Invio>
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[mxmxyz](mailto:mxmxyzgxyzt@gmail.com) | fixing typo in italian vim | 2020-09-09T02:42:53 | [4d8b097fb996](https://github.com/tldr-pages/tldr/commit/4d8b097fb9967cbb8e5210c6a66ae26cc4597ba0)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[gRastello](mailto:gabriele.rastello@edu.unito.it) | vim: add Italian translation. fixed typos | 2019-02-06T17:08:07 | [4c653cde036f](https://github.com/tldr-pages/tldr/commit/4c653cde036ff53a881e22a91281ec42419bf313)

