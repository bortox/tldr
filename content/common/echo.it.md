---
author: ['Marco Bonelli', 'Guido Lena Cota', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "echo, TLDR Pages"
description: "echo, Stampa a schermo gli argomenti forniti."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/echo>.

- Stampa un messaggio di testo. Nota: le virgolette sono opzionali:

```bash
echo "Hello World"
```

- Stampa un messaggio con il contenuto di variabili di ambiente:

```bash
echo "La mia path è $PATH"
```

- Stampa un messaggio senza il carattere di nuova linea finale:

```bash
echo -n "Hello World"
```

- Aggiungi un messaggio in coda ad un file:

```bash
echo "Hello World" >> file.txt
```

- Abilita l'interpretazione delle sequenze di escape con il backslash (caratteri speciali):

```bash
echo -e "Colonna 1\tColonna 2"
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo: add link (#5606) | 2021-03-30T15:54:21 | [206703144d57](https://github.com/tldr-pages/tldr/commit/206703144d576491dbcf66be20770c47ebe329d3)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Marco Bonelli](mailto:marco@mebeim.net) | ed: add Italian translation. | 2019-10-05T15:25:51 | [72c91362e4f9](https://github.com/tldr-pages/tldr/commit/72c91362e4f9886a304e35f0802978cc961f1151)
[Marco Bonelli](mailto:marco@mebeim.net) | echo: add Italian translation. | 2019-10-05T15:25:51 | [8d34c0e8d05a](https://github.com/tldr-pages/tldr/commit/8d34c0e8d05ae37586de77063fd2a8359c2efc8b)

