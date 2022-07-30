---
author: ['Guido Lena Cota']
date: 1602387977
title: "git ls-tree"
description: "git ls-tree, Elenca il contenuto di un oggetto albero."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-ls-tree>.

- Mostra il contenuto dell'albero su un ramo:

```bash
git ls-tree nome_ramo
```

- Mostra il contenuto dell'albero su un commit, procedendo ricorsivamente nei sotto-alberi:

```bash
git ls-tree -r hash_commit
```

- Mostra solo il nome dei file dell'albero su un commit:

```bash
git ls-tree --name-only hash_commit
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4627) * git-archive: add italian translation * git-bundle: add italian translation * git-cat-file: add [...] | 2020-10-11T05:46:17 | [b1a891a34a7a](https://github.com/tldr-pages/tldr/commit/b1a891a34a7a1d75b7b11fea3d9c3206713822f7)

