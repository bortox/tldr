---
author: ['Andreia Bohner']
date: 1658135504
title: "as, TLDR Pages"
description: "as, Montador (assembler) GNU portável."
categories: "osx"
---
> Principalmente destinado a montar a saída do `gcc` para ser usada pelo `ld`.

> Mais informações: <https://www.unix.com/man-page/osx/1/as/>.

- Montar (compilar) um arquivo, escrevendo a saída para `a.out`:

```bash
as arquivo.s
```

- Montar a saída para um determinado arquivo:

```bash
as arquivo.s -o saida.o
```

- Gerar saída mais rapidamente ignorando espaços em branco e pré-processamento de comentários. (Só deve ser usado para compiladores confiáveis)

```bash
as -f arquivo.s
```

- Incluir um determinado caminho na lista de diretórios para pesquisar os arquivos especificados nas diretivas `.include`:

```bash
as -I caminho/para/diretório arquivo.s
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Andreia Bohner](mailto:andreiabohner@gmail.com) | as: add pt_BR translation | 2022-07-18T11:11:44 | [b938852aaf30](https://github.com/tldr-pages/tldr/commit/b938852aaf30820a59d517c9cac1403b6ea6a441)

