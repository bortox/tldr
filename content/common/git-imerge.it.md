---
author: ['Marco Bonelli', 'lucas schneider']
date: 1610111394
title: "git-imerge, TLDR Pages"
description: "git-imerge, Esegui un'unione (merge) o rebase tra due rami Git in modo incrementale."
categories: "common"
---
> Eventuali conflitti tra i due rami sono tracciati in coppie di commit distinti, per semplificarne la risoluzione.

> Maggiori informazioni: <https://github.com/mhagger/git-imerge>.

- Avvia un rebase usando imerge (dopo aver fatto checkout sul ramo da spostare):

```bash
git imerge rebase ramo_su_cui_eseguire_il_rebase
```

- Avvia un'unione usando imerge (dopo aver fatto checkout sul ramo di destinazione):

```bash
git imerge merge ramo_da_unire
```

- Mostra con un diagramma ASCII lo stato di esecuzione dell'unione o rebase:

```bash
git imerge diagram
```

- Continua con l'operazione di imerge dopo aver risolto i conflitti (dopo aver aggiunto i file in conflitto con `git add`):

```bash
git imerge continue --no-edit
```

- Concludi l'operazione di imerge dopo aver risolto tutti i conflitti:

```bash
git imerge finish
```

- Interrompi l'operazione di imerge e ritorna al ramo precedente:

```bash
git-imerge remove && git checkout ramo_precedente
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Marco Bonelli](mailto:marco@mebeim.net) | git-imerge: add Italian translation. Co-authored-by: Guido Lena Cota <guido.lenacota@kreuzwerker.de> | 2020-01-11T00:21:56 | [53cae8a21780](https://github.com/tldr-pages/tldr/commit/53cae8a217809199b56f5bc73706114118354ea0)

