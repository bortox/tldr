---
author: ['Rui Alves']
date: 1570974840
title: "pdftk"
description: "pdftk, Conjunto de utilitários para manipular arquivos PDF."
categories: "common"
---
> Mais informações: <https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit>.

- Extrair conjuntos de páginas de um arquivo PDF (páginas 1 a 3, 5 e 6 a 10) e guardá-las num novo arquivo:

```bash
pdftk arquivo.pdf cat 1-3 5 6-10 output novo_arquivo.pdf
```

- Concatenar uma lista de arquivos PDF, guardando o resultado num novo arquivo:

```bash
pdftk arquivo1.pdf arquivo2.pdf arquivoN.pdf ... cat output novo_arquivo.pdf
```

- Partir cada página de um arquivo PDF num arquivo separado, com um padrão para o nome dos novos arquivos:

```bash
pdftk arquivo.pdf burst output página_%d.pdf
```

- Girar em 180° todas as páginas de um arquivo PDF:

```bash
pdftk arquivo.pdf cat 1-endsouth output novo_arquivo.pdf
```

- Girar a terceira página de um arquivo PDF em 90° no sentido horário, não modificando as restantes:

```bash
pdftk arquivo.pdf cat 1-2 3east 4-end output novo_arquivo.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rui Alves](mailto:up201606746@fe.up.pt) | pdftk: add pt_BR translation (#3383) | 2019-10-13T15:54:00 | [4cd868a94ad2](https://github.com/tldr-pages/tldr/commit/4cd868a94ad2a99316a52c423fceed9a447b2e9a)

