---
author: ['Marco Bonelli', 'lincc']
date: 1631818200
title: "exec, TLDR Pages"
description: "exec, Sostituisci il processo corrente con un altro."
categories: "common"
---
> Maggiori informazioni: <https://linuxcommand.org/lc3_man_pages/exech.html>.

- Sostituisci con il comando specificato utilizzando le variabili di ambiente correnti:

```bash
exec comando -con -flag
```

- Sostituisci con il comando specificato utilizzando un ambiente vuoto:

```bash
exec -c comando -con -flag
```

- Sostituisci con il comando specificato ed esegui il login con la shell predefinita:

```bash
exec -l comando -con -flag
```

- Sostituisci con il comando specificato e cambia il nome del processo:

```bash
exec -a nuovo_nome_processo comando -con -flag
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | exec, javac: add more information link (#6536) | 2021-09-16T20:50:00 | [53bb0828896b](https://github.com/tldr-pages/tldr/commit/53bb0828896bfcca7b5ce118fe241ef20c7a6fb0)
[Marco Bonelli](mailto:marco@mebeim.net) | exec: add Italian translation. | 2019-10-05T15:25:51 | [b8ddc94d6843](https://github.com/tldr-pages/tldr/commit/b8ddc94d68438847f8fcde87291c855a3c5be209)

