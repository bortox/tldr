---
author: ['Thiago Daniel Cagnoni de Pauli']
date: 1635359830
title: "diff"
description: "diff, Compara diretórios e arquivos."
categories: "common"
---
> Mais informações: <https://man7.org/linux/man-pages/man1/diff.1.html>.

- Compara arquivos (mostra as mudanças necessárias para transformar `arquivo_antigo` em `arquivo_novo`):

```bash
diff arquivo_antigo arquivo_novo
```

- Compara arquivos, ignorando espaço:

```bash
diff --ignore-all-space arquivo_antigo arquivo_novo
```

- Compara arquivos, mostrando diferenças lado a lado

```bash
diff --side-by-side arquivo_antigo arquivo_novo
```

- Compara arquivos, mostrando as diferenças de forma padronizada como feito por `git diff`:

```bash
diff --unified arquivo_antigo arquivo_novo
```

- Compara diretórios recursivamente, mostrando nomes de diretórios e arquivos diferentes e listando as diferenças entre os arquivos:

```bash
diff --recursive arquivo_antigo arquivo_novo
```

- Compara diretórios, mostrando apenas os nomes dos arquivos diferentes:

```bash
diff --recursive --brief arquivo_antigo arquivo_novo
```

- Cria um arquivo patch para o Git a partir das diferenças entre dois arquivos, tratando arquivos ausentes como vazios:

```bash
diff --text --unified --new-file arquivo_antigo arquivo_novo > diferenca.patch
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Thiago Daniel Cagnoni de Pauli](mailto:39651883+Float07@users.noreply.github.com) | date, diff, pip, pip3: add pt_BR translation (#7176) | 2021-10-27T20:37:10 | [c5c7a9ec9e81](https://github.com/tldr-pages/tldr/commit/c5c7a9ec9e81a904857cadad3a9c4de53035356c)

