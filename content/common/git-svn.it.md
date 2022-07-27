---
author: ['Guido Lena Cota', 'lucas schneider']
date: 1610111394
title: "git svn, TLDR Pages"
description: "git svn, Operazioni bidirezionali tra repository Subversion e Git."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-svn>.

- Clona un repository SVN:

```bash
git svn clone https://esempio.com/repo_subversion cartella_locale
```

- Clona un repository SVN a partire da uno specifico numero di revisione:

```bash
git svn clone -r1234:HEAD https://svn.esempio.net/subversion/repo cartella_locale
```

- Aggiorna una copia locale da un repository SVN remoto:

```bash
git svn rebase
```

- Scarica aggiornamenti da un repository SVN remoto senza spostare l'HEAD Git:

```bash
git svn fetch
```

- Invia un commit a un repository SVN:

```bash
git svn dcommit
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | change git to Git on missing pages | 2021-01-08T14:09:54 | [bd3ab881a0e2](https://github.com/tldr-pages/tldr/commit/bd3ab881a0e2d6fd53949148d7c268473572b7e3)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

