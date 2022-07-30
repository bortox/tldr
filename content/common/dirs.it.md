---
author: ['Marco Bonelli', 'marchersimon']
date: 1618869951
title: "dirs"
description: "dirs, Mostra o manipola uno stack di directory."
categories: "common"
---
> Uno stack di directory è una lista di directory recentemente visitate che può essere manipolata con i comandi `pushd` e `popd`.

> Maggiori informazioni: <https://www.gnu.org/software/bash/manual/bash.html#Directory-Stack-Builtins>.

- Mostra lo stack di directory dividendo i nomi con uno spazio:

```bash
dirs
```

- Mostra lo stack di directory una per riga:

```bash
dirs -p
```

- Mostra solo l'ennesima directory dello stack (gli indici partono da 0):

```bash
dirs +N
```

- Pulisci lo stack di directory:

```bash
dirs -c
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dirs: edit link Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-04-20T00:05:51 | [5d2fa2261db4](https://github.com/tldr-pages/tldr/commit/5d2fa2261db4d26e09c26f72f35d52e35dcf1bec)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Marco Bonelli](mailto:marco@mebeim.net) | dirs: add Italian translation. | 2019-07-21T01:59:28 | [22281ff8d4c7](https://github.com/tldr-pages/tldr/commit/22281ff8d4c76882499f9a2238303e6852075e91)

