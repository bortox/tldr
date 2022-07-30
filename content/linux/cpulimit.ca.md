---
author: ['Seifer23']
date: 1644117941
title: "cpulimit"
description: "cpulimit, Eina per limitar l'ús de la CPU en altres processos."
categories: "linux"
---
> Més informació: <http://cpulimit.sourceforge.net/>.

- Limita un procés existent amb PID 1234 perquè només utilitzi el 25% de CPU:

```bash
cpulimit --pid 1234 --limit 25%
```

- Limita un programa existent per el seu nom d'execució:

```bash
cpulimit --exe programa --limit 25
```

- Executa un programa determinat i limita el seu ús a només el 50% de la CPU:

```bash
cpulimit --limit 50 -- programa arg1 arg2 ...
```

- Executa un programa, limita l'ús de la CPU a 50% i executa cpulimit en segon pla:

```bash
cpulimit --limit 50 --background -- programa
```

- Mata el procés si l'ús de CPU del programa supera el 50%:

```bash
cpulimit --limit 50 --kill -- programa
```

- Regula el seu procés i els subprocessos perquè cap superi el 25% de CPU:

```bash
cpulimit --limit 25 --monitor-forks -- programa
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

