---
author: ['Lucas Gabriel Schneider', 'Marco Bonelli']
date: 1612112718
title: "elm"
description: "elm, Compila ed esegui file sorgente Elm."
categories: "common"
---
> Maggiori informazioni: <https://elm-lang.org>.

- Inizializza un progetto Elm, generando un file `elm.json`:

```bash
elm init
```

- Avvia una shell Elm interattiva:

```bash
elm repl
```

- Compila un file Elm, scrivendo il risultato in un file `index.html`:

```bash
elm make sorgente
```

- Compila un file Elm, scrivendo il risultato in un file JavaScript:

```bash
elm make sorgente --output=destinazione.js
```

- Avvia un web server locale che compila file Elm al caricamento delle pagine:

```bash
elm reactor
```

- Installa un pacchetto Elm da https://package.elm-lang.org:

```bash
elm install author/package
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | elm: add Italian translation. | 2019-10-05T15:25:51 | [d7d1c516506d](https://github.com/tldr-pages/tldr/commit/d7d1c516506d6a3e58b89b22b4bfc64c79709002)

