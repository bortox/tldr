---
author: ['FilipaDurao', 'bl-ue']
date: 1617130906
title: "batch, TLDR Pages"
description: "batch, Executar comandos num momento mais tarde quando a carga do sistema permitir."
categories: "common"
---
> O serviço atd (ou atrun) deve correr para atuais execuções.

> Mais informações: <https://man.archlinux.org/man/at.1>.

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
Lista de alterações feitas a esta documentação


Autor | Descrição | Formato de data ISO 8601 | Ligação a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[FilipaDurao](mailto:32716065+FilipaDurao@users.noreply.github.com) | batch: add Portuguese translation (#4502) | 2020-10-08T19:50:24 | [276287606fb3](https://github.com/tldr-pages/tldr/commit/276287606fb39517ea7899f03a64f58f37177415)

