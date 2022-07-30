---
author: ['Guido Lena Cota']
date: 1570361130
title: "git checkout"
description: "git checkout, Cambia rami o ripristina i file dell'albero di lavoro."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-checkout>.

- Crea e passa ad un nuovo ramo:

```bash
git checkout -b nome_ramo
```

- Crea e passa ad un nuovo ramo a partire dal riferimento specificato (ramo-locale, remote/ramo-remoto, tag sono alcuni esempi di riferimenti validi):

```bash
git checkout -b nome_ramo riferimento
```

- Passa ad un ramo locale esistente:

```bash
git checkout nome_ramo
```

- Passa ad un ramo remoto esistente:

```bash
git checkout --track nome_repository_remoto/nome_ramo
```

- Annulla tutte le modifiche nella cartella corrente che non sono state aggiunte all'area di stage (vedi `git reset` per più comandi simili):

```bash
git checkout .
```

- Annulla tutte le modifiche di un dato file non aggiunte all'area di stage:

```bash
git checkout nome_file
```

- Sostituisci un file con il contenuto del suo corrispondente localizzato su un altro ramo:

```bash
git checkout nome_ramo -- nome_file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | git-commands: add Italian translations (#3318) Add Italian translation for: - git - git-add - git-am - git-bisect - git-blame - git- [...] | 2019-10-06T13:25:30 | [4ee919925dd5](https://github.com/tldr-pages/tldr/commit/4ee919925dd57c445ca99ddaf183d0a51fedd29b)

