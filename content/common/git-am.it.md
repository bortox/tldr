---
author: ['Marco Bonelli', 'Guido Lena Cota', 'Lucas Gabriel Schneider']
date: 1612112718
title: "git am, TLDR Pages"
description: "git am, Applica file di patch. Utile quando si ricevono commit via email."
categories: "common"
---
> Vedi anche `git format-patch` per generare file di patch.

> Maggiori informazioni: <https://git-scm.com/docs/git-am>.

- Applica un file di patch:

```bash
git am percorso/al/file.patch
```

- Interrompi l'applicazione di un file di patch:

```bash
git am --abort
```

- Applica quanto possibile di un file di patch, salvando le parti non applicabili in file `.rej`:

```bash
git am --reject percorso/al/file.patch
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | it/git-am: fix typo. Co-authored-by: Guido Lena Cota <guido.lenacota@kreuzwerker.de> | 2020-01-11T00:21:56 | [a16222c55a86](https://github.com/tldr-pages/tldr/commit/a16222c55a865ecd7d1195fbf1538e830fddbfda)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | git-commands: add Italian translations (#3318) Add Italian translation for: - git - git-add - git-am - git-bisect - git-blame - git- [...] | 2019-10-06T13:25:30 | [4ee919925dd5](https://github.com/tldr-pages/tldr/commit/4ee919925dd57c445ca99ddaf183d0a51fedd29b)

