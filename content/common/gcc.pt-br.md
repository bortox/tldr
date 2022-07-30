---
author: ['Rui Alves', 'CleanMachine1', 'Marco Bonelli']
date: 1625254726
title: "gcc"
description: "gcc, Compilador de arquivos de código fonte C e C++, efetuando também as fases de pré-processamento, assembling e linking."
categories: "common"
---
> Mais informações: <https://gcc.gnu.org>.

- Compilar múltiplos arquivos de código fonte, produzindo um arquivo executável:

```bash
gcc arquivo_fonte1.c arquivo_fonte2.c --output arquivo_executável
```

- Habilitar avisos durante a compilação:

```bash
gcc arquivo_fonte.c -Wall -Og --output arquivo_executável
```

- Incluir bibliotecas de um local diferente:

```bash
gcc arquivo_fonte.c --output arquivo_executável -Icaminho/para/header -Lcaminho/para/biblioteca -lnome_biblioteca
```

- Compilar o código fonte para instruções Assembler:

```bash
gcc -S arquivo_fonte.c
```

- Compilar o código fonte sem efetuar a fase de linking:

```bash
gcc -c arquivo_fonte.c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | gcc: add long flag (#6182) | 2021-07-02T21:38:46 | [4c0aa1ac0cb7](https://github.com/tldr-pages/tldr/commit/4c0aa1ac0cb7541cd982040668faad0d842aa1a2)
[Marco Bonelli](mailto:marco@mebeim.net) | multiple pages (pt_BR): add missing trailing newline. | 2019-10-25T14:27:07 | [0d3209adbbbf](https://github.com/tldr-pages/tldr/commit/0d3209adbbbf41b9672a1bed97c13e7081c269f2)
[Rui Alves](mailto:up201606746@fe.up.pt) | gcc: add pt_BR translation (#3399) | 2019-10-24T04:09:26 | [aa48db41ee18](https://github.com/tldr-pages/tldr/commit/aa48db41ee188f5193b12171988d8f7c610ec066)

