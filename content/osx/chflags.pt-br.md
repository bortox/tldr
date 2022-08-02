---
author: ['Andréia Bohner']
date: 1659378325
title: "chflags"
description: "chflags, Altera flags de arquivo ou diretório."
categories: "osx"
---
> Mais informações: <https://ss64.com/osx/chflags.html>.

- Define a flag `hidden` para um arquivo:

```bash
chflags hidden caminho/para/arquivo
```

- Remove a flag `hidden` de um arquivo:

```bash
chflags nohidden caminho/para/arquivo
```

- Define recursivamente a flag `uchg` para um diretório:

```bash
chflags -R uchg caminho/para/diretório
```

- Remove recursivamente a flag `uchg` de um diretório:

```bash
chflags -R nouchg caminho/para/diretório
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andréia Bohner](mailto:andreiabohner@gmail.com) | osx/*: add pt_BR translations (#8269) | 2022-08-01T20:25:25 | [97b386939aa5](https://github.com/tldr-pages/tldr/commit/97b386939aa505be651794a55d3bea20b4f14ab2)

