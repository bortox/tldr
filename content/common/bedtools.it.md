---
author: ['pixel', 'Schneider', 'Marco Bonelli']
date: 1632941775
title: "bedtools, TLDR Pages"
description: "bedtools, Un coltellino svizzero di strumenti per analisi genomica."
categories: "common"
---
> Usato per intersecare, raggruppare, convertire e contare dati in formato BAM, BED, GFF/GTF, VCF.

> Maggiori informazioni: <https://bedtools.readthedocs.io>.

- Interseca i fili genetici delle sequenze contenute in due file diversi e salva il risultato:

```bash
bedtools intersect -a percorso/al/file_1 -b percorso/al/file_2 -s > percorso/al/file_output
```

- Interseca due file unendo il risultato a sinistra, ovvero riporta ogni feature da {{file_1}} e NULL dove non c'è sovrapposizione con {{file_2}}:

```bash
bedtools intersect -a percorso/al/file_1 -b percorso/al/file_2 -lof > percorso/al/file_output
```

- Usa un algoritmo più efficiente per intersecare due file precedentemente ordinati:

```bash
bedtools intersect -a percorso/al/file_1 -b percorso/al/file_2 -sorted > percorso/al/file_output
```

- Raggruppa file in base alle prime tre e la quinta colonna e raggruppa la sesta colonna sommandola:

```bash
bedtools groupby -i percorso/al/file -c 1-3,5 -g 6 -o sum
```

- Converti da formato BAM a BED:

```bash
bedtools bamtobed -i percorso/al/file.bam > percorso/al/file.bed
```

- Trova per tutte le proprietà in {{file_1}} la più vicina in {{file_2}} e scrivi la loro distanza in una ulteriore colonna (i file in input devono essere ordinati):

```bash
bedtools closest -a percorso/al/file_1.bed -b percorso/al/file_2.bed -d
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | *: normalize readthedocs.io more information links (#6593) | 2021-09-29T20:56:15 | [d22ca9676f6c](https://github.com/tldr-pages/tldr/commit/d22ca9676f6c02b19e6e1728f5ea777e7985c9d0)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\bedtools.md: add homepage | 2019-05-14T19:40:23 | [d7c4fb005ca2](https://github.com/tldr-pages/tldr/commit/d7c4fb005ca29a40f6496ecde5e4cc0ace3f2c4e)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | bedtools: add Italian translation. | 2019-01-28T19:10:19 | [bde43a6ec1ce](https://github.com/tldr-pages/tldr/commit/bde43a6ec1ce9f6f2eca33d00ec0eaa47e235970)

