---
author: ['Felipe Furquim']
date: 1633831138
title: "nano"
description: "nano, Editor de texto de linha de comando simples e fácil de usar. Um clone melhorado e gratuito de Pico."
categories: "common"
---
> Mais informações: <https://nano-editor.org>.

- Abre um novo arquivo no nano:

```bash
nano
```

- Abre um arquivo específico:

```bash
nano caminho/para/arquivo
```

- Abre um arquivo específico, posicionando o cursor na linha e coluna especificadas:

```bash
nano +linha,coluna caminho/para/arquivo
```

- Abre um arquivo específico e habilita soft wrapping:

```bash
nano --softwrap caminho/para/arquivo
```

- Abre um arquivo específico e indenta novas linhas para a indentação das linhas anteriores:

```bash
nano --autoindent caminho/para/arquivo
```

- Abre nano e cria um arquivo backup (`file~`) quando salva edições:

```bash
nano --backup caminho/para/arquivo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Felipe Furquim](mailto:49817522+FvFurquim@users.noreply.github.com) | cd, echo, grep, nano: add pt_BR translation (#6885) | 2021-10-10T03:58:58 | [349149546009](https://github.com/tldr-pages/tldr/commit/349149546009f1cf27f38f63d07a153bf02c67e0)

