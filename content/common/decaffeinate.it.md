---
author: ['Parnassius', 'Marco Bonelli']
date: 1602712645
title: "decaffeinate"
description: "decaffeinate, Converti script CoffeScript in JavaScript moderno."
categories: "common"
---
> Maggiori informazioni: <https://decaffeinate-project.org>.

- Converti un file CoffeeScript in JavaScript:

```bash
decaffeinate percorso/al/file.coffee
```

- Converti un file CoffeeScript v2 in JavaScript:

```bash
decaffeinate --use-cs2 percorso/al/file.coffee
```

- Converti `require` e `module.exports` in `import` ed `export`:

```bash
decaffeinate --use-js-modules percorso/al/file.coffee
```

- Converti un file CoffeeScript, permettendo di esportare nomi:

```bash
decaffeinate --loose-js-modules percorso/al/file.coffee
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Parnassius](mailto:Parnassius@users.noreply.github.com) | decaffeinate: fix typo in Italian translation (#4683) | 2020-10-14T23:57:25 | [a88a46cd28a0](https://github.com/tldr-pages/tldr/commit/a88a46cd28a011f8bc8f9fc81bc605f6b99cdf7a)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | decaffeinate: add Italian translation. | 2019-06-10T01:35:02 | [69861bc14316](https://github.com/tldr-pages/tldr/commit/69861bc143162eb0c5280943b433d2d0cd0bfaaf)

