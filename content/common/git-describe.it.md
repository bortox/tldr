---
author: ['lucas schneider', 'Guido Lena Cota']
date: 1610111394
title: "git describe"
description: "git describe, Rendi il nome di un oggetto Git più leggibile usando i riferimenti disponibili."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-describe>.

- Crea un nome univoco per il commit corrente (il nome contiene i tag più recenti, il numero di commit aggiuntivi, e l'hash breve del commit):

```bash
git describe
```

- Crea un nome di 4 cifre per l'hash breve del commit:

```bash
git describe --abbrev=4
```

- Genera un nome che includa anche il percorso di riferimento:

```bash
git describe --all
```

- Descrivi un tag Git:

```bash
git describe v1.0.0
```

- Crea un nome per l'ultimo commit di un dato ramo:

```bash
git describe nome_ramo
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | change git to Git on missing pages | 2021-01-08T14:09:54 | [bd3ab881a0e2](https://github.com/tldr-pages/tldr/commit/bd3ab881a0e2d6fd53949148d7c268473572b7e3)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4627) * git-archive: add italian translation * git-bundle: add italian translation * git-cat-file: add [...] | 2020-10-11T05:46:17 | [b1a891a34a7a](https://github.com/tldr-pages/tldr/commit/b1a891a34a7a1d75b7b11fea3d9c3206713822f7)

