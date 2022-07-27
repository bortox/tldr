---
author: ['Luis Felipe Santos do Nascimento']
date: 1620319123
title: "clear, TLDR Pages"
description: "clear, Limpa a tela do terminal."
categories: "common"
---
> Mais informações: <https://manned.org/clear>.

- Limpar a tela (equivalente a apertar Control-L no terminal Bash):

```bash
clear
```

- Limpar a tela mantendo o buffer de rolagem do terminal:

```bash
clear -x
```

- Especificar o tipo de terminal a ser limpado (por padrão é o valor da variável de ambiente `TERM`):

```bash
clear -T tipo_do_terminal
```

- Mostra a versão do `ncurses` usado pelo `clear`:

```bash
clear -V
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Luis Felipe Santos do Nascimento](mailto:luisfelipesdn12@gmail.com) | [, arduino-builder, arduino, bash, clear: add pt-BR translation (#5874) | 2021-05-06T18:38:43 | [0a5e31e1c7f3](https://github.com/tldr-pages/tldr/commit/0a5e31e1c7f3a48ec206ca07bb1ffb1cd0fb39c0)

