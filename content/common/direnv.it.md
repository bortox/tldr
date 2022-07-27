---
author: ['Francesco Franchina']
date: 1635196708
title: "direnv, TLDR Pages"
description: "direnv, Estensione della shell per aggiungere o rimuovere variabili d'ambiente in base alla cartella corrente."
categories: "common"
---
> Maggiori informazioni: <https://github.com/direnv/direnv>.

- Permette il caricamento del `.envrc` presente nella cartella corrente:

```bash
direnv allow .
```

- Revoca il permesso del `.envrc` presente nella cartella corrente:

```bash
direnv deny .
```

- Permette la modifica del `.envrc` nell'editor di testo predefinito, in seguito ricarica l'ambiente:

```bash
direnv edit .
```

- Ricarica l'ambiente corrente:

```bash
direnv reload
```

- Mostra delle informazioni di debug:

```bash
direnv status
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Francesco Franchina](mailto:cescus92@gmail.com) | direnv: clarification in the examples and Italian translation (#7001) | 2021-10-25T23:18:28 | [61b7666a76b1](https://github.com/tldr-pages/tldr/commit/61b7666a76b1d848c53b98af1194ccbe0c6d1789)

