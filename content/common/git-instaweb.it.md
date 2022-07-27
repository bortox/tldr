---
author: ['Guido Lena Cota']
date: 1602387977
title: "git instaweb, TLDR Pages"
description: "git instaweb, Helper per avviare un server gitweb."
categories: "common"
---
> Maggiori informazioni: <https://git-scm.com/docs/git-instaweb>.

- Avvia un server gitweb dal repository corrente:

```bash
git instaweb --start
```

- Resta in ascolto solo su localhost:

```bash
git instaweb --start --local
```

- Resta in ascolto su una porta specifica:

```bash
git instaweb --start --port 1234
```

- Usa un http daemon specifico:

```bash
git instaweb --start --httpd lighttpd|apache2|mongoose|plackup|webrick
```

- Avvia automaticamente anche un web browser:

```bash
git instaweb --start --browser
```

- Interrompi il server gitweb in esecuzione:

```bash
git instaweb --stop
```

- Riavvia il server gitweb in esecuzione:

```bash
git instaweb --restart
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | git*: add Italian translation (#4627) * git-archive: add italian translation * git-bundle: add italian translation * git-cat-file: add [...] | 2020-10-11T05:46:17 | [b1a891a34a7a](https://github.com/tldr-pages/tldr/commit/b1a891a34a7a1d75b7b11fea3d9c3206713822f7)

