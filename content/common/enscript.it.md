---
author: ['Marco Bonelli']
date: 1570281951
title: "enscript"
description: "enscript, Converti file di testo in PostScript, HTML, RTF, ANSI ed overstrike."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/enscript>.

- Genera un file PostScript da un file di testo:

```bash
enscript percorso/a/file_input --output=percorso/a/file_output
```

- Genera un file in un linguaggio differente da PostScript:

```bash
enscript percorso/a/file_input --language=linguaggio --output=percorso/a/file_output
```

- Genera un file PostScript con layout orizzontale, dividendo la pagina in colonne (massimo 9):

```bash
enscript percorso/a/file_input --columns=numero_colonne --landscape --output=percorso/a/file_output
```

- Mostra linguaggi e formati file disponibili per evidenziare la sintassi:

```bash
enscript --help-highlight
```

- Genera un file PostScript con evidenziazione della sintassi e colori per uno specifico linguaggio:

```bash
enscript percorso/a/file_input --color=1 --highlight=linguaggio --output=percorso/a/file_output
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | enscript: add Italian translation. | 2019-10-05T15:25:51 | [a0d2796ce987](https://github.com/tldr-pages/tldr/commit/a0d2796ce987776ac6c512dd773da7316c404c1e)

