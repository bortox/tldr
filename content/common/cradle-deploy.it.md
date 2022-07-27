---
author: ['Marco Bonelli']
date: 1560123302
title: "cradle deploy, TLDR Pages"
description: "cradle deploy, Gestisci distribuzioni Cradle."
categories: "common"
---
> Maggiori informazioni: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#deploy>.

- Distribuisci Cradle su un server:

```bash
cradle deploy production
```

- Distribuisci assets statici ad Amazon S3:

```bash
cradle deploy s3
```

- Distribuisci assets statici, inclusa la directory "components" di Yarn:

```bash
cradle deploy s3 --include-yarn
```

- Distribuisci assets statici, includendo la directory "upload":

```bash
cradle deploy s3 --include-upload
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | cradle-deploy: add Italian translation. | 2019-06-10T01:35:02 | [c1db39ba1436](https://github.com/tldr-pages/tldr/commit/c1db39ba14367218f59328eec9289f5f1b8b9d66)

