---
author: ['caduvieira', 'bl-ue', 'Carlos Vieira', 'lincc']
date: 1636372515
title: "aws s3"
description: "aws s3, Interface de linha de comando para AWS S3."
categories: "common"
---
> Provê armazenamento através de uma interface de web services.

> Mais informações: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3/index.html>.

- Exibe arquivos de um bucket:

```bash
aws s3 ls nome_do_bucket
```

- Sincroniza arquivos e diretórios locais para o bucket:

```bash
aws s3 sync caminho/para/arquivos s3://nome_do_bucket
```

- Sincroniza arquivos e diretórios do bucket para diretório local:

```bash
aws s3 sync s3://nome_do_bucket caminho/para/diretório
```

- Sincroniza arquivos e diretórios excluindo algo:

```bash
aws s3 sync caminho/para/arquivos s3://nome_do_bucket --exclude arquivo/não/sincronizado --exclude caminho/não/sincronizado/*
```

- Remove arquivo do bucket:

```bash
aws s3 rm s3://nome_do_bucket/caminho/do/arquivo
```

- Somente exibe a prévia das mudanças:

```bash
aws s3 qualquer_comando --dryrun
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: clean up token syntax delimiters (#5677) | 2021-04-04T02:08:57 | [289787c7e8c1](https://github.com/tldr-pages/tldr/commit/289787c7e8c1177742d23004198253154fe50c3c)
[caduvieira](mailto:3831408+caduvieira@users.noreply.github.com) | Update pages.pt_BR/common/aws-s3.md Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2020-11-01T14:37:16 | [2a9b42076e85](https://github.com/tldr-pages/tldr/commit/2a9b42076e85e432d987a4d655db32f3ed18c2f0)
[Carlos Vieira](mailto:3831408+caduvieira@users.noreply.github.com) | aws-s3: add pt_BR translation | 2020-11-01T14:37:16 | [17114391aa3a](https://github.com/tldr-pages/tldr/commit/17114391aa3a4d558bc7c5c8285c4061b7285663)

