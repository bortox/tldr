---
author: ['Tan A', 'Marco Bonelli']
date: 1616156811
title: "git commit"
description: "git commit, Salva file nell'area di stage in una nuova istantanea del tuo repository."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-commit>.

- Committa sul repository i file nell'area di stage con un messaggio:

```bash
git commit -m "messaggio"
```

- Aggiungi all'area di stage tutti i file modificati e committali con un messaggio:

```bash
git commit -a -m "messaggio"
```

- Sostituisci l'ultimo commit con le modifiche attualmente salvate nell'area di stage:

```bash
git commit --amend
```

- Committa solo i file specificati (tra quelli presenti nell'area di stage):

```bash
git commit percorso/al/file1 percorso/al/file2
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | git-commit: quote message argument (#5477) | 2021-03-19T13:26:51 | [d526739418e8](https://github.com/tldr-pages/tldr/commit/d526739418e89eba9a32b3b6acfe406abb9bdb50)
[Marco Bonelli](mailto:marco@mebeim.net) | git-commit: add Italian translation. Co-authored-by: Guido Lena Cota <guido.lenacota@kreuzwerker.de> | 2020-01-11T00:21:56 | [3785c55a7565](https://github.com/tldr-pages/tldr/commit/3785c55a7565793b9f5c56ef9d02b777e3e986a9)

