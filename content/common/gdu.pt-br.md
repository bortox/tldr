---
author: ['Gabriel Rodrigues']
date: 1634005028
title: "gdu"
description: "gdu, Analisador de uso de disco com interface de console."
categories: "common"
---
> Mais informações: <https://github.com/dundee/gdu>.

- Exibe interativamente o uso de disco do diretório atual:

```bash
gdu
```

- Exibe interativamente o uso de disco de um determinado diretório:

```bash
gdu caminho/para/diretório
```

- Exibe interativamente o uso de disco de todos os discos montados:

```bash
gdu --show-disks
```

- Exibe interativamente o uso de disco do diretório atual, mas ignora alguns subdiretórios:

```bash
gdu --ignore-dirs caminho/para/diretório1,caminho/para/diretório2,...
```

- Ignora caminhos por expressão regular:

```bash
gdu --ignore-dirs-pattern '.*[abc]+'
```

- Ignora diretórios ocultos:

```bash
gdu --no-hidden
```

- Imprime apenas o resultado, não entra no modo interativo:

```bash
gdu --non-interactive caminho/para/diretório
```

- Não mostra o progresso no modo não interativo (útil em scripts):

```bash
gdu --no-progress caminho/para/diretório
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gabriel Rodrigues](mailto:gabrxzvski@gmail.com) | gdu: add pt_BR translation | 2021-10-12T04:17:08 | [334940487dbb](https://github.com/tldr-pages/tldr/commit/334940487dbbeb10e14d6b6454dddec6b84f5f43)

