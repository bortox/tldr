---
author: ['Mario Gordon']
date: 1634640747
title: "cpulimit"
description: "cpulimit, Una herramienta para limitar el uso del CPU de otros procesos."
categories: "linux"
---
> Más información: <http://cpulimit.sourceforge.net/>.

- Limita un proceso existente con PID 1234 para que solo use el 25% del CPU:

```bash
cpulimit --pid 1234 --limit 25%
```

- Limita un programa existente por su nombre de ejecución:

```bash
cpulimit --exe programa --limit 25
```

- Ejecuta un programa determinado y limita su uso a solo el 50% del CPU:

```bash
cpulimit --limit 50 -- programa arg1 arg2 ...
```

- Ejecuta un programa, limita el uso del CPU a 50% y corre cpulimit en segundo plano:

```bash
cpulimit --limit 50 --background -- programa
```

- Mata su proceso si el uso del CPU del programa supera el 50%:

```bash
cpulimit --limit 50 --kill -- programa
```

- Regula su proceso y sus subprocesos para que ninguno supere el 25% del CPU:

```bash
cpulimit --limit 25 --monitor-forks -- programa
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Mario Gordon](mailto:80539604+maegop@users.noreply.github.com) | cpulimit: add Spanish translation (#7083) | 2021-10-19T12:52:27 | [32ab0c3c1317](https://github.com/tldr-pages/tldr/commit/32ab0c3c131777505f6d98607ac50f6626972e90)

