---
author: ['marchersimon']
date: 1631539482
title: "compgen, TLDR Pages"
description: "compgen, Um programa para auto completar comandos no Bash, ele é executado ao pressionar duas vezes a tecla TAB."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/bash/manual/bash.html#index-compgen>.

- Exibir todos os comandos que você pode executar:

```bash
compgen -c
```

- Exibir todos os alias:

```bash
compgen -a
```

- Exibir todas as funções que você pode executar:

```bash
compgen -A function
```

- Exibir todas as palavras reservadas do shell:

```bash
compgen -k
```

- Exibir todos os comandos/alias que iniciam com o termo 'ls':

```bash
compgen -ac ls
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | compgen, eval, export, file: move to common (#6508) | 2021-09-13T15:24:42 | [ac46610ce633](https://github.com/tldr-pages/tldr/commit/ac46610ce6338c5a56328c69fbe047a08d663d78)

