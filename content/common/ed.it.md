---
author: ['Marco Bonelli', 'marchersimon']
date: 1659075216
title: "ed"
description: "ed, L'originale editor di testo Unix."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/ed/manual/ed_manual.html>.

- Avvia ed per editare un documento vuoto (che può essere salvato come nuovo file nella directory corrente):

```bash
ed
```

- Avvia ed per editare un documento vuoto, con `:` come indicatore del prompt di comandi:

```bash
ed -p :
```

- Avvia ed per editare un file esistente (mostra il numero di byte del file caricato):

```bash
ed -p : percorso/al/file
```

- Attiva o disattiva la stampa di spiegazioni per gli errori (di default, le spiegazioni non sono stampate ed appare solo un `?`):

```bash
H
```

- Aggiungi del testo al documento corrente. Indica il completamento inserendo un punto da solo su una nuova linea:

```bash
a<Enter>text_to_insert<Enter>.
```

- Stampa l'intero documento (`,` è una scorciatoia per il range `1,$` che copre dall'inizio alla fine del documento):

```bash
,p
```

- Scrivi il documento corrente su un nuovo file (il nome del file può essere omesso se `ed` è stato avviato con un file esistente):

```bash
w nome_file
```

- Termina ed:

```bash
q
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ed: add link (#5532) | 2021-03-29T18:34:34 | [609014c1978e](https://github.com/tldr-pages/tldr/commit/609014c1978e51d6b5872b3b47c3000f732a0f21)
[Marco Bonelli](mailto:marco@mebeim.net) | ed: add Italian translation. | 2019-10-05T15:25:51 | [72c91362e4f9](https://github.com/tldr-pages/tldr/commit/72c91362e4f9886a304e35f0802978cc961f1151)

