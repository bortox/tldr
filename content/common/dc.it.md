---
author: ['Marco Bonelli', 'marchersimon']
date: 1618869951
title: "dc, TLDR Pages"
description: "dc, Calcolatore a precisione arbitraria. Usa la notazione polacca inversa (RPN)."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/bc/manual/dc-1.05/html_mono/dc.html>.

- Avvia il calcolatore in modalità interattiva:

```bash
dc
```

- Esegui uno script dc da file:

```bash
dc -f file
```

- Calcola 4 per 5 [4 5 *], sottrai 17 [17 -], e stampa [p] il risultato (utilizzando echo):

```bash
echo "4 5 * 17 - p"| dc
```

- Setta il numero di posizioni decimali a 7 [7 k], calcola 5 diviso -3 [5 _3/] e stampa [p] il risultato (utilizzando dc -e):

```bash
dc -e "7 k 5 _3 / p"
```

- Calcola il rapporto aureo, phi: setta il numero di posizioni decimali a 100 [100 k], e calcola la radice di 5 [5 v] più 1 [1 +], diviso due [2 /] e stampa [p] il risultato:

```bash
dc -e "100 k 5 v 1 + 2 / p"
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | dc: edit link | 2021-04-20T00:05:51 | [12349ec3a507](https://github.com/tldr-pages/tldr/commit/12349ec3a50759fae6bc2a35214f6979650dbd66)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | dc: add Italian translation. | 2019-06-10T01:35:02 | [60088ef77e54](https://github.com/tldr-pages/tldr/commit/60088ef77e54fea8c6386c561588861e0b53f215)

