---
author: ['Gabriel Rodrigues']
date: 1634005028
title: "fmt"
description: "fmt, Reformata um arquivo de texto juntando seus parágrafos e limitando a largura da linha a um determinado número de caracteres (75 por padrão)."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/coreutils/fmt>.

- Reformata um arquivo:

```bash
fmt caminho/para/arquivo
```

- Reformata um arquivo produzindo linhas de saída de (no máximo) `n` caracteres:

```bash
fmt -w n caminho/para/arquivo
```

- Reformata um arquivo sem unir linhas menores do que a largura fornecida:

```bash
fmt -s caminho/para/arquivo
```

- Reformata um arquivo com espaçamento uniforme (1 espaço entre palavras e 2 espaços entre parágrafos):

```bash
fmt -u caminho/para/arquivo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gabriel Rodrigues](mailto:gabrxzvski@gmail.com) | fmt: add pt_BR translation | 2021-10-12T04:17:08 | [0dfdf46de5d5](https://github.com/tldr-pages/tldr/commit/0dfdf46de5d51747321de35def1d2166bb314966)

