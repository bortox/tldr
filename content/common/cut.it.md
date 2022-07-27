---
author: ['Waldir Pimenta', 'Marco Bonelli', 'Dario Vladović', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1617292466
title: "cut, TLDR Pages"
description: "cut, Taglia dividendo in campi stdin o file."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/cut>.

- Estrai i primi 16 caratteri di ogni riga da stdin:

```bash
cut -c 1-16
```

- Estrai i primi 16 caratteri di ogni riga da un dato file:

```bash
cut -c 1-16 file
```

- Estrai tutto dal terzo carattere fino alla fine di ogni riga:

```bash
cut -c 3-
```

- Estrai il quinto campo di ogni linea, utilizzando i due punti come separatore di campo (il default è tab):

```bash
cut -d':' -f5
```

- Estrai il secondo e decimo campo di ogni linea, utilizzando il punto e virgola come delimitatore:

```bash
cut -d';' -f2,10
```

- Estrai i campi dal terzo in poi di ogni linea, utilizzando lo spazio come delimitatore:

```bash
cut -d' ' -f3-
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cut: add link (#5576) | 2021-03-30T13:39:27 | [f311aa47f394](https://github.com/tldr-pages/tldr/commit/f311aa47f394998f831ebd4af66733b85cc9c08a)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | cut: add Italian translation. | 2019-06-10T01:35:02 | [8516224380a9](https://github.com/tldr-pages/tldr/commit/8516224380a9c1dfa0e2a20a6ac37141d3c653ad)

