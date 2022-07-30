---
author: ['Bruno Eduardo de Souza Medeiros']
date: 1603908399
title: "choco upgrade"
description: "choco upgrade, Atualizar um ou mais pacotes com Chocolatey."
categories: "windows"
---
> Mais informações: <https://chocolatey.org/docs/commands-upgrade>.

- Atualizar um ou mais pacotes separados por espaço:

```bash
choco upgrade pacote(s)
```

- Atualizar para uma versão específica de um pacote:

```bash
choco upgrade pacote --version versão
```

- Atualizar todos pacotes:

```bash
choco upgrade all
```

- Atualizar todos os pacotes, exceto os especificados separados por virgula:

```bash
choco upgrade all --except "pacote(s)"
```

- Confirmar todos prompts automaticamente:

```bash
choco upgrade pacote --yes
```

- Especifique uma fonte personalizada para receber pacotes:

```bash
choco upgrade pacote --source url_do_pacote|apelido
```

- Fornecer um nome e uma senha para autenticação:

```bash
choco upgrade pacote --user usuário --password senha
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Bruno Eduardo de Souza Medeiros](mailto:50559336+brunoeduardodev@users.noreply.github.com) | choco-*: add pt_BR translation (#4868) | 2020-10-28T19:06:39 | [c105fe4d88ab](https://github.com/tldr-pages/tldr/commit/c105fe4d88ab88c28163213bd25cae1fcdfebdc6)
[Bruno Eduardo de Souza Medeiros](mailto:50559336+brunoeduardodev@users.noreply.github.com) | choco, choco-install, choco-upgrade: add pt_BR translation (#4587) | 2020-10-10T21:38:41 | [6e2e4195b6ca](https://github.com/tldr-pages/tldr/commit/6e2e4195b6cabc330c05c22b026e47dbc7ec3446)

