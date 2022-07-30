---
author: ['FilipaDurao', 'bl-ue', 'marchersimon']
date: 1659075216
title: "batch, TLDR Pages"
description: "batch, Executar comandos num momento mais tarde quando a carga do sistema permitir."
categories: "common"
---
> O serviço atd (ou atrun) deve correr para atuais execuções.

> Mais informações: <https://manned.org/batch>.

- Executar comandos da entrada padrão (premir `Ctrl + D` quando terminado):

```bash
batch
```

- Executar um comando da entrada padrão:

```bash
echo "./criar_copia_bd.sh" | batch
```

- Executar comandos de um dado ficheiro:

```bash
batch -f caminho/para/ficheiro
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[FilipaDurao](mailto:32716065+FilipaDurao@users.noreply.github.com) | batch: add Portuguese translation (#4502) | 2020-10-08T19:50:24 | [276287606fb3](https://github.com/tldr-pages/tldr/commit/276287606fb39517ea7899f03a64f58f37177415)

