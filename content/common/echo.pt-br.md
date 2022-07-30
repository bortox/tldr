---
author: ['Felipe Furquim']
date: 1633831138
title: "echo"
description: "echo, Imprime os argumentos passados."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/coreutils/echo>.

- Imrpime uma mensagem de texto. Nota: aspas são opcionais:

```bash
echo "Uma mensagem"
```

- Imprime uma mensagem com as variáveis de ambiente:

```bash
echo "Meu path é $PATH"
```

- Imprime uma mensagem sem adicionar uma nova linha em seguida:

```bash
echo -n "Uma mensagem"
```

- Adiciona uma messagem no arquivo:

```bash
echo "Uma mensagem" >> arquivo.txt
```

- Habilita interpretação dos códigos de escape após barra invetida (caracteres especiais):

```bash
echo -e "Coluna 1\tColuna 2"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Felipe Furquim](mailto:49817522+FvFurquim@users.noreply.github.com) | cd, echo, grep, nano: add pt_BR translation (#6885) | 2021-10-10T03:58:58 | [349149546009](https://github.com/tldr-pages/tldr/commit/349149546009f1cf27f38f63d07a153bf02c67e0)

