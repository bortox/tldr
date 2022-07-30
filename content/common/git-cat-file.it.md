---
author: ['lucas schneider', 'Guido Lena Cota']
date: 1610111394
title: "git cat-file"
description: "git cat-file, Visualizza il contenuto di un oggetto Git nel repository o mostrane dimensione e tipo."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-cat-file>.

- Mostra la dimen[s]ione del commit HEAD in byte:

```bash
git cat-file -s HEAD
```

- Mostra il [t]ipo (blob, albero, commit, tag) di un oggetto Git:

```bash
git cat-file -t 8c442dc3
```

- Stam[p]a il contenuto di un oggetto Git, formattato in base al tipo:

```bash
git cat-file -p HEAD~2
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4627) * git-archive: add italian translation * git-bundle: add italian translation * git-cat-file: add [...] | 2020-10-11T05:46:17 | [b1a891a34a7a](https://github.com/tldr-pages/tldr/commit/b1a891a34a7a1d75b7b11fea3d9c3206713822f7)

