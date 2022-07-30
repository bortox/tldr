---
author: ['Guido Lena Cota']
date: 1604320952
title: "git remote"
description: "git remote, Gestisci i collegamenti remoti ('remote') di un repository locale."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-remote>.

- Mostra l'elenco dei collegamenti remoti, con il loro nome e URL:

```bash
git remote -v
```

- Mostra informazioni su un remote:

```bash
git remote show nome_remote
```

- Aggiungi un remote:

```bash
git remote add nome_remote url_remote
```

- Modifica l'URL di un remote (usa `--add` per preservare gli URL esistenti):

```bash
git remote set-url nome_remoto nuovo_url
```

- Elimina un remote:

```bash
git remote remove nome_remote
```

- Rinomina un remote:

```bash
git remote rename vecchio_nome nuovo_nome
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4734) * git-prune: add it translation * git-reflog: add it translation * git-remote: add it [...] | 2020-11-02T13:42:32 | [83ddae952d5f](https://github.com/tldr-pages/tldr/commit/83ddae952d5f3e99161567eb39dece72465f77fa)

