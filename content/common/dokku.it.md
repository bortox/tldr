---
author: ['Marco Bonelli']
date: 1570281951
title: "dokku"
description: "dokku, Mini-Heroku basato su Docker (PaaS, Platform As A Service)."
categories: "common"
---
> Distribuisci facilmente molteplici app sul tuo server in diversi linguaggi utilizzando un singolo comando `git-push`.

> Maggiori informazioni: <https://github.com/dokku/dokku>.

- Elenca app in esecuzione:

```bash
dokku apps
```

- Crea un'app:

```bash
dokku apps:create nome_app
```

- Rimuovi un'app:

```bash
dokku apps:destroy nome_app
```

- Installa un plugin:

```bash
dokku plugin:install url_completo_repo
```

- Collega un database ad un'app:

```bash
dokku db:link nome_db nome_app
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | dokku: add Italian translation. | 2019-10-05T15:25:51 | [c489aa9bd4d4](https://github.com/tldr-pages/tldr/commit/c489aa9bd4d4aaa876f2b890a3436b27a03e12db)

