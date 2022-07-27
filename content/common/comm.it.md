---
author: ['Marco Bonelli', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "comm, TLDR Pages"
description: "comm, Seleziona o ignora linee comuni a due file. Entrambi i file devono essere ordinati."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/comm>.

- Produci tre colonne separate da tab: linee solo nel primo file, linee solo nel secondo file, e linee comuni ad entrambi:

```bash
comm file1 file2
```

- Stampa solo le linee comune ad entrambi i file:

```bash
comm -12 file1 file2
```

- Stampa solo le lin comuni ad entrambi i file, leggendone uno da standard input:

```bash
cat file1 | comm -12 - file2
```

- Filtra le linee trovate solo nel primo file, salvando il risultato in un terzo file:

```bash
comm -23 file1 file2 > file3
```

- Filtra le linee trovate solo nel secondo file, con due file che non sono ordinati:

```bash
comm -13 <(sort file1) <(sort file2)
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | comm: add link (#5574) | 2021-03-30T13:45:00 | [d2f1b60f45aa](https://github.com/tldr-pages/tldr/commit/d2f1b60f45aa596ac50271f9f18ad69817e3eb26)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | comm: add Italian translation. | 2019-06-10T01:35:02 | [85182402d90e](https://github.com/tldr-pages/tldr/commit/85182402d90ed637d60a891a160b2870c4c00a75)

