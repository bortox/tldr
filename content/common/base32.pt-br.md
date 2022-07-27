---
author: ['alexsantee']
date: 1635360041
title: "base32, TLDR Pages"
description: "base32, Codifica ou decodifica um arquivo ou a entrada padrão (stdin) de/para Base32, para a saída padrão (stdout)."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/coreutils/base32>.

- Codifica um arquivo:

```bash
base32 nome_do_arquivo
```

- Decodifica um arquivo:

```bash
base32 --decode nome_do_arquivo
```

- Codifica a partir de stdin:

```bash
algum_comando | base32
```

- Decodifica a partir de stdin:

```bash
algum_comando | base32 --decode
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[alexsantee](mailto:40058461+alexsantee@users.noreply.github.com) | base32: add pt_BR translation (#7168) | 2021-10-27T20:40:41 | [ddb5e2155ce8](https://github.com/tldr-pages/tldr/commit/ddb5e2155ce8ed1b16bbd5e545ecf8323b678f64)

