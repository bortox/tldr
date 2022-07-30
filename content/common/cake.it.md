---
author: ['Marco Bonelli']
date: 1563667168
title: "cake"
description: "cake, Strumento da linea di comando per il framework CakePHP."
categories: "common"
---
> Maggiori informazioni: <https://cakephp.org>.

- Mostra informazioni sull'attuale app ed i comandi disponibili:

```bash
cake
```

- Elenca le rotte disponibili:

```bash
cake routes
```

- Pulisci le cache di configurazione:

```bash
cake cache clear_all
```

- Costruisci la cache dei metadati:

```bash
cake schema_cache build --connection connessione
```

- Pulisci la cache dei metadati:

```bash
cake schema_cache clear
```

- Pulisci una tabella di cache:

```bash
cake schema_cache clear nome_tabella
```

- Avvia un web server di sviluppo (porta predefinita 8765):

```bash
cake server
```

- Avvia una shell REPL interattiva:

```bash
cake console
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | cake: add Italian translation. | 2019-07-21T01:59:28 | [e8b380ab3a23](https://github.com/tldr-pages/tldr/commit/e8b380ab3a2333a6805e738097b1866e5b4edf6f)

