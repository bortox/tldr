---
author: ['bl-ue', 'Tommaso']
date: 1610731489
title: "binwalk, TLDR Pages"
description: "binwalk, Strumento per l'analisi di file binari."
categories: "linux"
---
> Maggiori informazioni: <https://github.com/ReFirmLabs/binwalk>.

- Scansiona un file binario:

```bash
binwalk percorso/a/file
```

- Estrae file da un binario, specificando la cartella di output:

```bash
binwalk --extract --directory cartella_di_output percorso/a/file
```

- Estrae file in maniera ricorsiva a partire da un binario, limitando la profondità di ricorsione a 2 livelli:

```bash
binwalk --extract --matryoshka --depth 2 percorso/a/file
```

- Estrae file da un binario utilizzando una particolare firma (ad esempio il MIME Type):

```bash
binwalk --dd 'png image:png' percorso/a/file
```

- Analizza l'entropia di un binario e salva il grafico con lo stesso filename del binario, con l'estensione `.png` in fondo:

```bash
binwalk --entropy --save percorso/a/file
```

- Combina analisi di entropia, firme e opcode in un unico comando:

```bash
binwalk --entropy --signature --opcodes percorso/a/file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Tommaso](mailto:p.tommy93@gmail.com) | binwalk: add Italian translation (#4769) | 2020-10-24T16:10:43 | [beff2972f428](https://github.com/tldr-pages/tldr/commit/beff2972f42878ac3188dfc38c2660916462704a)

