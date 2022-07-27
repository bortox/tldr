---
author: ['Marco Bonelli', 'Schneider']
date: 1559564381
title: "ansiweather, TLDR Pages"
description: "ansiweather, Uno script per mostrare le attuali condizioni meteo nel tuo terminale."
categories: "common"
---
> Maggiori informazioni: <https://github.com/fcambus/ansiweather>.

- Mostra una previsione usando unità SI per i prossimi cinque giorni in Rzeszow (Polonia):

```bash
ansiweather -u metric -f 5 -l Rzeszow,PL
```

- Mostra una previsione con simboli e informazioni sulla luce solare per la tua posizione attuale:

```bash
ansiweather -s true -d true
```

- Mostra una previsione con informazioni su vento ed umidità per la tua posizione attuale:

```bash
ansiweather -w true -h true
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\ansiweather.md: add homepage | 2019-05-14T19:40:23 | [d044d0e8c439](https://github.com/tldr-pages/tldr/commit/d044d0e8c439afa4c06655258ca86e77e9d7466b)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | ansiweather: add Italian translation. | 2019-01-28T19:10:19 | [1d342fe47a8d](https://github.com/tldr-pages/tldr/commit/1d342fe47a8d38c7355db3b44a8cbb1b6a96b1cd)

