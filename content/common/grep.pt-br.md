---
author: ['Felipe Furquim']
date: 1633831138
title: "grep"
description: "grep, Acha padrões em arquivos usando expressões regulares."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/grep/manual/grep.html>.

- Pesquisa por um padrão em um arquivo:

```bash
grep "padrão_pesquisado" caminho/para/arquivo
```

- Pesquisa por uma string exata (desabilita expressões regulares):

```bash
grep --fixed-strings "string_exata" caminho/para/arquivo
```

- Pesquisa por um padrão em todos os arquivos recursivamente em um diretório, mostrando o número das linhas das correspondências, ignorando arquivos binários:

```bash
grep --recursive --line-number --binary-files=without-match "padrão_pesquisado" caminho/para/diretório
```

- Usa expressões regulares estendidas (suporta `?`, `+`, `{}`, `()` and `|`), no modo insensível a maiúsculas e minúsculas:

```bash
grep --extended-regexp --ignore-case "padrão_pesquisado" caminho/para/arquivo
```

- Imprime 3 linhas de contexto em volta, antes ou depois de cada correspondência:

```bash
grep --context|before-context|after-context=3 "padrão_pesquisado" caminho/para/arquivo
```

- Imprime o nome do arquivo e o número da linha para cada correspondência:

```bash
grep --with-filename --line-number "padrão_pesquisado" caminho/para/arquivo
```

- Pesquisa por linhas que correspondem a um padrão, imprimindo apenas o texto correspondido:

```bash
grep --only-matching "padrão_pesquisado" caminho/para/arquivo
```

- Pesquisa stdin para linhas que não correspondem a um padrão:

```bash
cat caminho/para/arquivo | grep --invert-match "padrão_pesquisado"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Felipe Furquim](mailto:49817522+FvFurquim@users.noreply.github.com) | cd, echo, grep, nano: add pt_BR translation (#6885) | 2021-10-10T03:58:58 | [349149546009](https://github.com/tldr-pages/tldr/commit/349149546009f1cf27f38f63d07a153bf02c67e0)

