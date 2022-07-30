---
author: ['Bruno Eduardo de Souza Medeiros']
date: 1603908399
title: "choco list"
description: "choco list, Exibir uma lista de pacotes com Chocolatey."
categories: "windows"
---
> Mais informações: <https://chocolatey.org/docs/commands-list>.

- Exibir todos pacotes disponíveis:

```bash
choco list
```

- Exibir todos pacotes instalados localmente:

```bash
choco list --local-only
```

- Exibir uma lista incluindo programas locais:

```bash
choco list --include-programs
```

- Exibir apenas pacotes aprovados:

```bash
choco list --approved-only
```

- Especificar uma fonte personalizada para exibir os pacotes:

```bash
choco list --source url_da_fonte|apelido
```

- Fornecer um nome e uma senha para autenticação:

```bash
choco list --user usuário --password senha
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Bruno Eduardo de Souza Medeiros](mailto:50559336+brunoeduardodev@users.noreply.github.com) | choco-*: add pt_BR translation (#4868) | 2020-10-28T19:06:39 | [c105fe4d88ab](https://github.com/tldr-pages/tldr/commit/c105fe4d88ab88c28163213bd25cae1fcdfebdc6)

