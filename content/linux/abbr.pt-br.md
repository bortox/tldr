---
author: ['Luis']
date: 1658329726
title: "abbr"
description: "abbr, Gerencie abreviações para fish-shell."
categories: "linux"
---
> Palavras definidas pelo usuário são substituídas por frases longas assim que são digitadas.

> Mais informações: <https://fishshell.com/docs/current/cmds/abbr.html>.

- Adicione uma nova abreviação:

```bash
abbr --add nome_abreviacao comando orgumentos_comando
```

- Renomear uma abreviação existente:

```bash
abbr --rename nome_antigo novo_nome
```

- Apagar uma abreviação existente:

```bash
abbr --erase nome_abreviacao
```

- Importar abreviações definidas em outro host via SSH:

```bash
ssh nome_host abbr --show | source
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Luis](mailto:CasperBraske@users.noreply.github.com) | abbr: add pt_BR translation (#8211) | 2022-07-20T17:08:46 | [98dfcc76fa7f](https://github.com/tldr-pages/tldr/commit/98dfcc76fa7fbac8260653d4c6589a5aedfc1a7f)

