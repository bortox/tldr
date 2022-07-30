---
author: ['Marco Bonelli']
date: 1560123302
title: "blackfire"
description: "blackfire, Strumento di profilazione da linea di comando per PHP."
categories: "common"
---
> Maggiori informazioni: <https://blackfire.io>.

- Inizializza e configura il client Blackfire:

```bash
blackfire config
```

- Lancia l'agent Blackfire:

```bash
blackfire agent
```

- Lancia l'agent Blackfire su uno specifico socket:

```bash
blackfire agent --socket="tcp://127.0.0.1:8307"
```

- Lancia il profiler su uno specifico programma:

```bash
blackfire run php percorso/al/file.php
```

- Lancia il profiler e raccogli 10 campioni:

```bash
blackfire --samples=10 run php percorso/al/file.php
```

- Lancia il profiler e mostra i risultati in output come JSON:

```bash
blackfire --json run php percorso/al/file.php
```

- Carica un file del profiler sul servizio web di Blackfire:

```bash
blackfire upload percorso/al/file
```

- Mostra lo stato dei profili sul servizio web di Blackfire:

```bash
blackfire status
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | blackfire: add Italian translation. | 2019-06-10T01:35:02 | [8e8ae280e8a3](https://github.com/tldr-pages/tldr/commit/8e8ae280e8a371b440c652736e71f2a0fe72ed5f)

