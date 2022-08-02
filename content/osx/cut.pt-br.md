---
author: ['Andréia Bohner']
date: 1659378325
title: "cut"
description: "cut, Recorta campos de stdin ou arquivos."
categories: "osx"
---
> Mais informações: <https://manned.org/man/freebsd-13.0/cut.1>.

- Imprime um intervalo específico de caracteres/campos de cada linha:

```bash
comando | cut -c|f 1|1,10|1-10|1-|-10
```

- Imprime um intervalo de cada linha com um delimitador específico:

```bash
comando | cut -d "," -c 1
```

- Imprime um intervalo de cada linha de um arquivo específico:

```bash
cut -c 1 caminho/para/arquivo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andréia Bohner](mailto:andreiabohner@gmail.com) | osx/*: add pt_BR translations (#8269) | 2022-08-01T20:25:25 | [97b386939aa5](https://github.com/tldr-pages/tldr/commit/97b386939aa505be651794a55d3bea20b4f14ab2)

