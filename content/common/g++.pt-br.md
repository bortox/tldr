---
author: ['Marco Bonelli', 'Rui Alves']
date: 1572006427
title: "gplusplus, TLDR Pages"
description: "gplusplus, Compilador de arquivos de código fonte C++."
categories: "common"
---
> Parte do GCC (GNU Compiler Collection).

> Mais informações: <https://gcc.gnu.org>.

- Compilar um arquivo de código fonte para um binário executável:

```bash
g++ arquivo_fonte.cpp -o arquivo_executável
```

- Compilar mostrando todos os erros e avisos:

```bash
g++ arquivo_fonte.cpp -Wall -o arquivo_executável
```

- Compilar utilizando um padrão específico da linguagem (C++98/C++11/C++14/C++17):

```bash
g++ arquivo_fonte.cpp -std=standard_linguagem -o arquivo_executável
```

- Compilar incluindo bibliotecas localizadas em um local diferente do arquivo de código fonte:

```bash
g++ arquivo_fonte.cpp -o arquivo_executável -Icaminho/para/header -Lcaminho/para/biblioteca -lnome_biblioteca
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | multiple pages (pt_BR): add missing trailing newline. | 2019-10-25T14:27:07 | [0d3209adbbbf](https://github.com/tldr-pages/tldr/commit/0d3209adbbbf41b9672a1bed97c13e7081c269f2)
[Rui Alves](mailto:up201606746@fe.up.pt) | g++: add pt_BR translation (#3402) | 2019-10-14T20:29:48 | [171bdd5a51cc](https://github.com/tldr-pages/tldr/commit/171bdd5a51ccd457ab2677cfe787eef10587ad9b)

