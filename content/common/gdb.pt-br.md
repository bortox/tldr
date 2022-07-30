---
author: ['André Almeida']
date: 1603125498
title: "gdb"
description: "gdb, O depurador GNU."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/gdb>.

- Depurar um executável:

```bash
gdb executável
```

- Vincular um processo ao gdb:

```bash
gdb -p PID
```

- Depurar usando um arquivo de "core dump":

```bash
gdb -c core executável
```

- Executa um dado comando do gdb ao iniciar:

```bash
gdb -ex "comandos" executável
```

- Inicia o gdb passando argumentos para o executável:

```bash
gdb --args executável argumento1 argumento2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[André Almeida](mailto:andrealmeid@collabora.com) | gdb: add pt_BR translation (#4709) | 2020-10-19T18:38:18 | [4f2d04c03b15](https://github.com/tldr-pages/tldr/commit/4f2d04c03b157d1f2fdbf36218f69e56cb7d283c)

