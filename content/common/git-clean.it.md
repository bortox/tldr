---
author: ['Guido Lena Cota', 'lucas schneider']
date: 1610111394
title: "git clean, TLDR Pages"
description: "git clean, Elimina i file non tracciati dall'albero di lavoro."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-clean>.

- Elimina i file che non sono tracciati da Git:

```bash
git clean
```

- Elimina in modo interattivo i file non tracciati da Git:

```bash
git clean -i
```

- Mostra quali file non tracciati sarebbero eliminati, senza però eliminarli davvero:

```bash
git clean --dry-run
```

- Forza l'eliminazione dei file non tracciati da Git:

```bash
git clean -f
```

- Forza l'eliminazione delle cartelle non tracciate da Git:

```bash
git clean -fd
```

- Elimina i file non tracciati, compresi quelli da ignorare elencati in `.gitignore` e `.git/info/exclude`:

```bash
git clean -x
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | git-commands: add Italian translations (#3318) Add Italian translation for: - git - git-add - git-am - git-bisect - git-blame - git- [...] | 2019-10-06T13:25:30 | [4ee919925dd5](https://github.com/tldr-pages/tldr/commit/4ee919925dd57c445ca99ddaf183d0a51fedd29b)

