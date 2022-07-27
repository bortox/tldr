---
author: ['Luca Lumetti']
date: 1619893759
title: "nvim, TLDR Pages"
description: "nvim, Neovim, un editor di testo basato su Vim che offre molti diversi modi di manipolare e navigare il testo."
categories: "common"
---
> Premere `i` per entrare in modalità inserimento (insert mode), `<Esc>` per uscire e tornare alla modalità normale (normal mode).

> Maggiori informazioni: <https://neovim.io>.

- Aprire un file:

```bash
nvim file
```

- Entrare nella modalità per scrivere testo (insert mode):

```bash
<Esc>i
```

- Copiare ("yank") o cancellare ("delete") la linea corrente (può poi essere copiara con `p` o `P`):

```bash
<Esc>yy|dd
```

- Annullare l'ultima operazione fatta:

```bash
<Esc>u
```

- Cercare uno specifico pattern nel file (premere `n`/`N` per navigare tra le occorrenze successive/precedenti):

```bash
<Esc>/patter_da_cercare<Enter>
```

- Eseguire una sostituzione tramite espressione regolare nell'intero file:

```bash
<Esc>:%s/espressione_regolare/sostituzione//g<Enter>
```

- Salvare (scrivere) il file per poi uscire:

```bash
<Esc>:wq<Enter>
```

- Uscire senza salvare:

```bash
<Esc>:q!<Enter>
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Luca Lumetti](mailto:lumetti.luca@gmail.com) | xkill, xxd, nvim: add italian translation (#5862) | 2021-05-01T20:29:19 | [9ccc49d98f38](https://github.com/tldr-pages/tldr/commit/9ccc49d98f381d0a97e1cef45eb7e3e2c883a97a)

