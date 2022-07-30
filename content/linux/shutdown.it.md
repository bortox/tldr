---
author: ['Triad']
date: 1635770315
title: "shutdown"
description: "shutdown, Spegni e riavvia il sistema."
categories: "linux"
---
> Maggiori informazioni: <https://manned.org/shutdown.8>.

- Spegni il sistema immediatamente:

```bash
shutdown -h now
```

- Riavvia il sistema immediatamente:

```bash
shutdown -r now
```

- Riavvia il sistema in 5 minuti:

```bash
shutdown -r +5 &
```

- Spegni il sistema alle 13:

```bash
shutdown -h 13:00
```

- Annulla un'operazione programmata di riavvio o spegnimento:

```bash
shutdown -c
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Triad](mailto:33317323+MrTriad@users.noreply.github.com) | shutdown: add Italian translation (#7320) | 2021-11-01T13:38:35 | [5fef26fc102d](https://github.com/tldr-pages/tldr/commit/5fef26fc102d8ea21c1ae0c8d070551bb30367e8)

