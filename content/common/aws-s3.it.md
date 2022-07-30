---
author: ['Marco Bonelli', 'lincc']
date: 1636372515
title: "aws s3"
description: "aws s3, CLI per AWS S3 - fornisce spazio di archiviazione tramite le interfacce di Amazon Web Services."
categories: "common"
---
> Maggiori informazioni: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3/index.html>.

- Mostra file in un bucket:

```bash
aws s3 ls nome_bucket
```

- Sincronizza file e directory locali su un bucket:

```bash
aws s3 sync percorso/ai/file s3://nome_bucket
```

- Sincronizza file e directory da un bucket in locle:

```bash
aws s3 sync s3://nome_bucket path/to/target
```

- Sincronizza file e directory escludendo alcuni file o directory:

```bash
aws s3 sync percorso/ai/file s3://nome_bucket --exclude percorso/al/file --exclude directory/*
```

- Rimuovi un file dal bucket:

```bash
aws s3 rm s3://bucket/percorso/al/file
```

- Mostra solo un'anteprima dei cambiamenti:

```bash
aws s3 qualsiasi_comando --dryrun
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | aws-s3: add Italian translation. | 2019-01-28T19:10:19 | [3fb017528e42](https://github.com/tldr-pages/tldr/commit/3fb017528e4268be030087e93558450693ad98b5)

