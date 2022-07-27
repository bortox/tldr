---
author: ['Guido Lena Cota', 'lucas schneider']
date: 1610111394
title: "git difftool, TLDR Pages"
description: "git difftool, Mostra le modifiche ai file tracciati usando uno strumento Diff esterno. Accetta le stesse opzioni e argomenti di Git diff."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-difftool>.

- Elenca gli strumenti Diff disponibili:

```bash
git difftool --tool-help
```

- Imposta meld come strumento Diff predefinito:

```bash
git config --global diff.tool "meld"
```

- Usa lo strumento Diff predefinito per mostrare le modifiche nell'area di stage:

```bash
git difftool --staged
```

- Uso uno specifico strumento Diff (opendiff) per mostrare le modifiche a partire da un dato commit:

```bash
git difftool --tool=opendiff commit
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | git-difftool: : add it translation (#4387) The translation 'diff tool' -> 'strumento Diff' is based on: https://www.microsoft.com/it- [...] | 2020-10-01T20:25:10 | [5c60eeec9cfc](https://github.com/tldr-pages/tldr/commit/5c60eeec9cfc79a0fef8a0bcbeb91803a3d5304c)

