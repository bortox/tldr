---
author: ['Bruno Eduardo de Souza Medeiros']
date: 1603908399
title: "choco info"
description: "choco info, Exibir informações detalhadas de um pacote com Chocolatey."
categories: "windows"
---
> Mais informações: <https://chocolatey.org/docs/commands-info>.

- Exibir informações sobre um pacote específico:

```bash
choco info pacote
```

- Exibir informação para um pacote local:

```bash
choco info pacote --local-only
```

- Especificar uma fonte personalizada para receber as informações de um pacote:

```bash
choco info pacote --source url_da_fonte|apelido
```

- Fornecer um nome e uma senha para autenticação:

```bash
choco info pacote --user apelido --password senha
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Bruno Eduardo de Souza Medeiros](mailto:50559336+brunoeduardodev@users.noreply.github.com) | choco-*: add pt_BR translation (#4868) | 2020-10-28T19:06:39 | [c105fe4d88ab](https://github.com/tldr-pages/tldr/commit/c105fe4d88ab88c28163213bd25cae1fcdfebdc6)

