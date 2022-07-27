---
author: ['Guido Lena Cota', 'bl-ue', 'lucas schneider']
date: 1610124748
title: "git switch, TLDR Pages"
description: "git switch, Passa ad altri rami. Richiede versioni di Git successive alla 2.23."
categories: "common"
---
> Vedi anche `git checkout`.

> Maggiori informazioni: <https://git-scm.com/docs/git-switch>.

- Passa ad un altro ramo esistente:

```bash
git switch nome_ramo
```

- Crea un nuovo ramo e passa a quel ramo:

```bash
git switch --create nome_ramo
```

- Crea un nuovo ramo a partire da un commit esistente e passa a quel ramo:

```bash
git switch --create nome_ramo commit
```

- Torna al ramo precedente:

```bash
git switch -
```

- Passa ad un ramo ed aggiorna tutti i moduli secondari associati:

```bash
git switch --recurse-submodules nome_ramo
```

- Passa ad un ramo e uniscilo automaticamente al ramo corrente, include le modifiche non committate:

```bash
git switch --merge nome_ramo
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-switch: fix more information link The old one led to an HTTP 500 because of the trailing /. | 2021-01-08T17:52:28 | [79b1257ea24f](https://github.com/tldr-pages/tldr/commit/79b1257ea24ff4293a7eca44482fa4eb6daf1a61)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4737) * git-send-email: add it translation * git-shortlog: add it translation * git-show-branch: add [...] | 2020-11-03T08:49:29 | [d8f628d0055b](https://github.com/tldr-pages/tldr/commit/d8f628d0055bff98d5d64a811ea6349dfe245116)

