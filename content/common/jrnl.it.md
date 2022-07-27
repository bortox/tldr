---
author: ['Noemi']
date: 1635016143
title: "jrnl, TLDR Pages"
description: "jrnl, Una semplice applicazione da linea di comando per tenere un diario."
categories: "common"
---
> Maggiori informazioni: <http://jrnl.sh>.

- Inserisci una nuova nota con il tuo editor:

```bash
jrnl
```

- Inserimento veloce di una nota:

```bash
jrnl today at 3am: titolo. contenuto
```

- Mostra le ultime dieci note inserite:

```bash
jrnl -n 10
```

- Mostra tutto quello che è successo dall'inizio dello scorso anno fino all'inizio di marzo:

```bash
jrnl -from "last year" -until march
```

- Modifica tutte le note taggate con "texas" e "history":

```bash
jrnl @texas -and @history --edit
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Noemi](mailto:33022202+noemi3@users.noreply.github.com) | jrnl: add Italian translation (#7016) | 2021-10-23T21:09:03 | [7906944e89b0](https://github.com/tldr-pages/tldr/commit/7906944e89b0c5e6df562e239dbf91151365cd9f)

