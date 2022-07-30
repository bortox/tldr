---
author: ['Dario Vladović', 'pxgamer', 'marchersimon']
date: 1617292466
title: "rm"
description: "rm, Rimuovi file o directory."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/rm>.

- Rimuovi file:

```bash
rm percorso/a/file1 percorso/a/file2 ...
```

- Rimuovi ricorsivamente una directory e tutti i suoi contenuti:

```bash
rm -r percorso/alla/directory
```

- Rimuovi ricorsivamente una directory, senza chiedere conferma o mostrare messaggi di errore:

```bash
rm -rf percorso/alla/directory
```

- Rimuovi file interattivamente, chiedendo conferma prima di rimuovere ogni file:

```bash
rm -i file(s)
```

- Rimuovi file in modalità verbosa, scrivendo un messaggio a schermo per ogni file rimosso:

```bash
rm -v percorso/a/un/file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | rm: add link (#5552) | 2021-03-30T09:16:08 | [62668322a827](https://github.com/tldr-pages/tldr/commit/62668322a8278797489c72f005849770fe3f51fb)
[pxgamer](mailto:owzie123@gmail.com) | ls,rm: remove trailing whitespace from filenames | 2019-02-12T15:37:55 | [d0aee29566fa](https://github.com/tldr-pages/tldr/commit/d0aee29566fa8e0ee65fb30febff321e015af12c)

