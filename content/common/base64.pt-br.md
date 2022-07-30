---
author: ['stefanyramos']
date: 1634140190
title: "base64"
description: "base64, Codifica ou decodifica um arquivo ou uma entrada padrão (stdin) de/para Base64, para uma saída padrão (stdout)."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/coreutils/base64>.

- Codifica o conteúdo de um arquivo para base64 e grava o resultado em stdout:

```bash
base64 nome_arquivo
```

- Decodifica o conteúdo de um arquivo em base64 e grava o resultado em stdout:

```bash
base64 --decode nome_arquivo
```

- Codifica a partir de stdin:

```bash
algum_comando | base64
```

- Decodifica a partir de stdin:

```bash
algum_comando | base64 --decode
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[stefanyramos](mailto:40060993+stefanyramos@users.noreply.github.com) | base64: add pt_BR translation (#6890) | 2021-10-13T17:49:50 | [ad5757ca686b](https://github.com/tldr-pages/tldr/commit/ad5757ca686b161630e9fd3e8e270772b35ed94e)

