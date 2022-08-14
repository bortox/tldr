---
author: ['Luis Braschi']
date: 1660422880
title: "addr2line"
description: "addr2line, Converte endereços de um binário em nomes de arquivos e números de linha."
categories: "linux"
---
> Mais informações: <https://manned.org/addr2line>.

- Exibe o nome do arquivo e o número da linha do código-fonte de um endereço de instrução de um executável:

```bash
addr2line --exe=caminho/do/executavel endereco
```

- Exibe o nome da função, nome do arquivo e número da linha:

```bash
addr2line --exe=caminho/do/executavel --functions endereco
```

- Desembaraça o nome da função em código C++:

```bash
addr2line --exe=caminho/do/executavel --functions --demangle endereco
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Luis Braschi](mailto:CasperBraske@users.noreply.github.com) | addr2line: add pt_BR translation (#8341) | 2022-08-13T22:34:40 | [06b5cd6803fc](https://github.com/tldr-pages/tldr/commit/06b5cd6803fc4d6cb4ca25c5519b5714dc4ee740)

