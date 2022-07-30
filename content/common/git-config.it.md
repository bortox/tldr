---
author: ['lucas schneider', 'Marco Bonelli']
date: 1610111394
title: "git config"
description: "git config, Configura le impostazioni di uno o piu repository Git."
categories: "common"
---
> Le configurazioni possono essere sia locali (per il repository corrente) che globali (per l'utente corrente).

> Maggiori informazioni: <https://git-scm.com/docs/git-config>.

- Elenca solo le opzioni di configurazione locali (salvate in `.git/config` nel repository corrente):

```bash
git config --list --local
```

- Elenca solo le opzioni di configurazione globali (salvate in `~/.gitconfig`):

```bash
git config --list --global
```

- Elenca tutte le opzioni di configurazione impostate, sia locali che globali:

```bash
git config --list
```

- Mostra il valore di una data opzione di configurazione:

```bash
git config alias.unstage
```

- Imposta il valore globale di una data opzione di configurazione:

```bash
git config --global alias.unstage "reset HEAD --"
```

- Ripristina una opzione di configurazione globale al suo valore di default:

```bash
git config --global --unset alias.unstage
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Marco Bonelli](mailto:marco@mebeim.net) | git-config: add Italian translation. Co-authored-by: Guido Lena Cota <guido.lenacota@kreuzwerker.de> | 2020-01-11T00:21:56 | [b767da10ada2](https://github.com/tldr-pages/tldr/commit/b767da10ada2fe23de78bdcd3860a8682d94d602)

