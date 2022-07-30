---
author: ['Guido Lena Cota']
date: 1604320952
title: "git rebase"
description: "git rebase, Applica i commit di un ramo su un ramo differente."
categories: "common"
---
> Tipicamente usato per riallineare (rebase) due rami, creando copie dei commit nella nuova posizione.

> Maggiori informazioni: <https://git-scm.com/docs/git-rebase>.

- Riallinea il ramo corrente con il ramo specificato:

```bash
git rebase ramo_della_nuova_base
```

- Avvia un rebase interattivo, che consente di riordinare, omettere, unire o modificare i commit:

```bash
git rebase -i nome_ramo_o_commit_hash
```

- Prosegui con un rebase che era stato sospeso da un errore di unione, dopo aver risolto i conflitti:

```bash
git rebase --continue
```

- Prosegui con un rebase che era stato sospeso da conflitti di unione, ignorando i commit in conflitto:

```bash
git rebase --skip
```

- Interrompi un rebase in corso (ad esempio perché interrotto da un conflitto di unione):

```bash
git rebase --abort
```

- Sposta parti del ramo corrente su una base differente, specificando la vecchia base di partenza:

```bash
git rebase --onto nuova_base vecchia_base
```

- Applica gli ultimi 5 commit locali, consentendo di riordinarli, ometterli, unirli o modificarli:

```bash
git rebase -i HEAD~5
```

- Risolvi automaticamente i conflitti a favore del ramo di versione corrente (la parola chiave `theirs` ha qui un significato opposto):

```bash
git rebase -X theirs nome_ramo
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4734) * git-prune: add it translation * git-reflog: add it translation * git-remote: add it [...] | 2020-11-02T13:42:32 | [83ddae952d5f](https://github.com/tldr-pages/tldr/commit/83ddae952d5f3e99161567eb39dece72465f77fa)

