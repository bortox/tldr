---
author: ['Schneider']
date: 1600285645
title: "scc"
description: "scc, Utilitário escrito em GO que conta linhas de código."
categories: "common"
---
> Mais informações: <https://github.com/boyter/scc>.

- Mostrar o número de linhas de código no diretório atual:

```bash
scc
```

- Mostrar o número de linhas de código de um diretório especificado:

```bash
scc caminho/para/diretorio
```

- Mostrar o número de linhas de código por arquivo:

```bash
scc --by-file
```

- Mostrar o resultado usando um formato específico (formato padrão é o `tabular`):

```bash
scc --format tabular|wide|json|csv|cloc-yaml|html|html-table
```

- Contar apenas os arquivos com as extensões especificadas:

```bash
scc --include-ext go, java, js
```

- Excluir diretórios da contagem:

```bash
scc --exclude-dir .git,.hg
```

- Mostrar output organizado de acordo com o parâmetro especificado (organização padrão é `files`):

```bash
scc --sort files|name|lines|blanks|code|comments|complexity
```

- Mostra a tela de ajuda:

```bash
scc -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Schneider](mailto:lucas.schneider@sap.com) | nativefier,scc: fix endline | 2020-09-16T21:47:25 | [3823d18d4a71](https://github.com/tldr-pages/tldr/commit/3823d18d4a71d3eb037579bbde7e06815093f9c3)
[Schneider](mailto:lucas.schneider@sap.com) | scc: add brazilian portuguese translation | 2020-09-16T21:47:25 | [f28e46e301bb](https://github.com/tldr-pages/tldr/commit/f28e46e301bb11f3590189aef9d15e6cd118c9d5)

