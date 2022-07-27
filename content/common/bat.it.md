---
author: ['Marco Bonelli', 'marchersimon']
date: 1633112881
title: "bat, TLDR Pages"
description: "bat, Stampa e concatena file."
categories: "common"
---
> Un clone di `cat` con syntax highlighting e integrazione Git.

> Maggiori informazioni: <https://github.com/sharkdp/bat>.

- Stampa i contenuti di un file su standard output:

```bash
bat file
```

- Concatena diversi file in un unico file:

```bash
bat file1 file2 > file_finale
```

- Aggiungi il contenuto di diversi file alla fine di un file:

```bash
bat file1 file2 >> file_finale
```

- Numera tutte le linee stampate:

```bash
bat -n file
```

- Evidenzia la sintassi di un file JSON:

```bash
bat --language json file.json
```

- Mostra tutti i linguaggi supportati:

```bash
bat --list-languages
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | bat: add Italian translation. | 2019-01-28T19:10:19 | [514954074d0e](https://github.com/tldr-pages/tldr/commit/514954074d0e973e7bbbccc4616c8fe162928db6)

