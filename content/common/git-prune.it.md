---
author: ['bl-ue', 'Lucas Gabriel Schneider', 'Guido Lena Cota', 'lucas schneider']
date: 1612369364
title: "git prune"
description: "git prune, Elimina dal database degli oggetti quelli non più raggiungibili."
categories: "common"
---
> Questo comando è usato più spesso internamente da Git gc piuttosto che in modo diretto.

> Maggiori informazioni: <https://git-scm.com/docs/git-prune>.

- Elenca quali oggetti saranno eliminati da Git prune senza eliminarli definitivamente:

```bash
git prune --dry-run
```

- Elimina gli oggetti non raggiungibili e stampane un elenco su stdout:

```bash
git prune --verbose
```

- Elimina gli oggetti non raggiungibili, mostrando lo stato di avanzamento:

```bash
git prune --progress
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4734) * git-prune: add it translation * git-reflog: add it translation * git-remote: add it [...] | 2020-11-02T13:42:32 | [83ddae952d5f](https://github.com/tldr-pages/tldr/commit/83ddae952d5f3e99161567eb39dece72465f77fa)

