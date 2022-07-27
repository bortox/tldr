---
author: ['Guido Lena Cota']
date: 1602387977
title: "git archive, TLDR Pages"
description: "git archive, Crea un archivio dei file nell'albero di lavoro."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-archive>.

- Crea un archivio tar del contenuto in HEAD e stampa il risultato su standard output:

```bash
git archive --verbose HEAD
```

- Crea un archivio zip del contenuto in HEAD e stampa il risultato su standard output:

```bash
git archive --verbose --format=zip HEAD
```

- Come sopra, ma scrivi l'archivio zip su file:

```bash
git archive --verbose --output=percorso/al/file.zip HEAD
```

- Crea un archivio tar dell'ultimo commit sul ramo specificato:

```bash
git archive --output=percorso/al/file.tar nome_ramo
```

- Crea un archivio tar del contenuto di una specifica cartella:

```bash
git archive --output=percorso/al/file.tar HEAD:percorso/alla/directory
```

- Anteponi un percorso ad ogni file cosí da archiviarlo in una cartella specifica:

```bash
git archive --output=percorso/al/file.tar --prefix=percorso/da/anteporre/ HEAD
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4627) * git-archive: add italian translation * git-bundle: add italian translation * git-cat-file: add [...] | 2020-10-11T05:46:17 | [b1a891a34a7a](https://github.com/tldr-pages/tldr/commit/b1a891a34a7a1d75b7b11fea3d9c3206713822f7)

