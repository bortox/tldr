---
author: ['Guido Lena Cota', 'bl-ue']
date: 1610124748
title: "git ls-remote, TLDR Pages"
description: "git ls-remote, Elenca i riferimenti in un repository remoto dato un nome o un URL."
categories: "common"
---
> Qualora né nome né URL siano specificati, il ramo predefinito è upstream - se configurato - oppure origin.

> Maggiori informazioni: <https://git-scm.com/docs/git-ls-remote>.

- Mostra tutti i riferimenti nel repository remoto predefinito:

```bash
git ls-remote
```

- Mostra solo i riferimenti HEAD nel repository remoto predefinito:

```bash
git ls-remote --heads
```

- Mostra solo i riferimenti a tag nel repository remoto predefinito:

```bash
git ls-remote --tags
```

- Mostra tutti i riferimenti da un repository remoto dato un nome o URL:

```bash
git ls-remote url_repository
```

- Filtra i riferimenti da un repository remoto rispetto a un dato criterio:

```bash
git ls-remote nome_repository "criterio"
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-ls-remote: fix more information link | 2021-01-08T17:52:28 | [d4cf28316104](https://github.com/tldr-pages/tldr/commit/d4cf28316104bab7545110f1ca33e07f478fcf53)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4627) * git-archive: add italian translation * git-bundle: add italian translation * git-cat-file: add [...] | 2020-10-11T05:46:17 | [b1a891a34a7a](https://github.com/tldr-pages/tldr/commit/b1a891a34a7a1d75b7b11fea3d9c3206713822f7)

