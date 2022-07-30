---
author: ['Schneider', 'Marco Bonelli']
date: 1559564381
title: "berks"
description: "berks, Gestore di dipendenze per Chef cookbooks."
categories: "common"
---
> Maggiori informazioni: <https://docs.chef.io/berkshelf.html>.

- Installa dipendenze cookbook in una repo locale:

```bash
berks install
```

- Aggiorna uno specifico cookbook e le sue dipendenze:

```bash
berks update cookbook
```

- Carica un cookbook sul server di Chef:

```bash
berks upload cookbook
```

- Mostra le dipendenze di un cookbook:

```bash
berks contingent cookbook
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\berks.md:add homepage | 2019-05-14T19:40:23 | [8b06f65ad3ef](https://github.com/tldr-pages/tldr/commit/8b06f65ad3ef2108d879510de015a4fecf9be194)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | berks: add Italian translation. | 2019-01-28T19:10:19 | [84f5ff98c91e](https://github.com/tldr-pages/tldr/commit/84f5ff98c91e9d3ca97269b9894245330658a067)

