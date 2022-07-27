---
author: ['Gabriel Rodrigues']
date: 1633877353
title: "history, TLDR Pages"
description: "history, Histórico de linha da comando."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/bash/manual/html_node/Bash-History-Builtins.html>.

- Exibe a lista de histórico de comandos com números de linha:

```bash
history
```

- Exibe os últimos 20 comandos (em `zsh` ele exibe todos os comandos a partir do 20º):

```bash
history 20
```

- Limpa a lista do histórico de comandos (apenas para o shell `bash` atual):

```bash
history -c
```

- Sobrescreve o arquivo de histórico com o histórico do shell `bash` atual (frequentemente combinado com `history -c` para limpar o histórico):

```bash
history -w
```

- Deleta a entrada do histórico no deslocamento especificado:

```bash
history -d deslocamento
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Gabriel Rodrigues](mailto:gabrxzvski@gmail.com) | history: add pt_BR translation | 2021-10-10T16:49:13 | [e8182af0817b](https://github.com/tldr-pages/tldr/commit/e8182af0817b2d8259203b2633e25c54ad0175c1)

