---
author: ['Guido Lena Cota', 'lucas schneider']
date: 1610111394
title: "git show, TLDR Pages"
description: "git show, Mostra vari tipi di oggetti Git (commit, tag, etc.)."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-show>.

- Mostra informazioni sull'ultimo commit (hash, messaggio, modifiche, ed altri metadati):

```bash
git show
```

- Mostra informazioni su un dato commit:

```bash
git show commit
```

- Mostra informazioni sul commit associato ad un tag specifico:

```bash
git show tag
```

- Mostra informazioni sul terzo commit dalla cima del ramo:

```bash
git show ramo~3
```

- Mostra il messaggio di commit su linea singola, senza mostrare il diff:

```bash
git show --oneline -s commit
```

- Mostra solo la lista dei file modificati in un commit:

```bash
git show --stat commit
```

- Mostra il contenuto di un file ad una data revisione (ad esempio, in un ramo, tag o commit):

```bash
git show revisione:percorso/al/file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

