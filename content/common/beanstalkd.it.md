---
author: ['Marco Bonelli', 'Schneider']
date: 1559564381
title: "beanstalkd, TLDR Pages"
description: "beanstalkd, Un semplice e generico gestore di code di lavoro."
categories: "common"
---
> Maggiori informazioni: <https://beanstalkd.github.io/>.

- Avvia beanstalkd, ascoltando sulla porta 11300:

```bash
beanstalkd
```

- Avvia beanstalkd ascoltando su porta ed un indirizzo dati:

```bash
beanstalkd -l indirizzo_ip -p numero_porta
```

- Rendi le code di lavoro persistenti salvandole su disco:

```bash
beanstalkd -b percorso/a/directory_persistente
```

- Sincronizza con una cartella persistente ogni 500 millisecondi:

```bash
beanstalkd -b percorso/a/directory_persistente -f 500
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\beanstalkd.md:add homepage | 2019-05-14T19:40:23 | [d3873ee5080e](https://github.com/tldr-pages/tldr/commit/d3873ee5080e1bb55105872546fed3a3c553b4f1)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | beanstalkd: add Italian translation. | 2019-01-28T19:10:19 | [550f544fb053](https://github.com/tldr-pages/tldr/commit/550f544fb0533a559b74870f38bc8f0cf9e3e116)

