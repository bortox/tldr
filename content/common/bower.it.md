---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider', 'Schneider']
date: 1612112718
title: "bower, TLDR Pages"
description: "bower, Un manager di pacchetti ottimizzato per sviluppo web front-end."
categories: "common"
---
> Un pacchetto può essere una abbreviazione utente/repo GitHub, un endpoint Git, un URL o un pacchetto registrato.

> Maggiori informazioni: <https://bower.io/>.

- Installa le dipendenze di un progetto, listate nel suo file `bower.json`:

```bash
bower install
```

- Installa pacchetti nella directory bower_components:

```bash
bower install pacchetto1 pacchetto2 ...
```

- Disinstalla pacchetti localmente rimuovendolo dalla directory bower_components:

```bash
bower uninstall pacchetto1 pacchetto2
```

- Elenca pacchetti locali e possibili aggiornamenti:

```bash
bower list
```

- Mostra aiuto per un comando di bower:

```bash
bower help comando
```

- Crea un file bower.json per i tuoi pacchetti:

```bash
bower init
```

- Installa unoa specifica versione di una dipendenza ed aggiungila al file `bower.json`:

```bash
bower install nome_locale=pacchetto#versione --save
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\bower.md: add homepage | 2019-05-14T19:40:23 | [9d808dac7c08](https://github.com/tldr-pages/tldr/commit/9d808dac7c08f4c96aad26b5cf05b2083b57887b)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | bower: add Italian translation. | 2019-01-28T19:10:19 | [d2cb482d460d](https://github.com/tldr-pages/tldr/commit/d2cb482d460d738a9d9be2b045980f64ccbbc4c0)

