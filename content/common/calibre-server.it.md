---
author: ['Schneider', 'bl-ue', 'Marco Bonelli']
date: 1621541621
title: "calibre-server"
description: "calibre-server, Un'applicazione server che può essere usata per distribuire e-book in una rete."
categories: "common"
---
> Gli e-book devono prima essere importati nella libreria usando la GUI o calibredb.

> Parte del manager di e-book Calibre.

> Maggiori informazioni: <https://manual.calibre-ebook.com/generated/en/calibre-server.html>.

- Avvia un server per distribuire e-book. Accesso a http://localhost:8080:

```bash
calibre-server
```

- Avvia il server su una specifica porta. Accesso a http://localhost:porta:

```bash
calibre-server --port porta
```

- Proteggi il server con username e password:

```bash
calibre-server --username username --password password
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\calibre-server.md: add homepage | 2019-05-14T19:40:23 | [d514786c6fb6](https://github.com/tldr-pages/tldr/commit/d514786c6fb61a2fddd02ee2b319d3b7a1879e74)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | calibre-server: add Italian translation. | 2019-01-28T19:10:19 | [a2f534f25954](https://github.com/tldr-pages/tldr/commit/a2f534f25954829da57c7c5a65b81e1728f0826e)

