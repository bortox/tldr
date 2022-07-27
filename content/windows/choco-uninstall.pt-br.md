---
author: ['Bruno Eduardo de Souza Medeiros']
date: 1603908399
title: "choco uninstall, TLDR Pages"
description: "choco uninstall, Desinstalar um pacote ou mais com Chocolatey."
categories: "windows"
---
> Mais informações: <https://chocolatey.org/docs/commands-uninstall>.

- Desinstalar um pacote ou mais separado por espaços:

```bash
choco uninstall pacote(s)
```

- Desinstalar uma versão específica de um pacote:

```bash
choco uninstall pacote --version versão
```

- Confirmar todos prompts automaticamente:

```bash
choco uninstall pacote --yes
```

- Remover todas dependências ao desinstalar:

```bash
choco uninstall pacote --remove-dependencies
```

- Desinstalar todos os pacotes:

```bash
choco uninstall all
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Bruno Eduardo de Souza Medeiros](mailto:50559336+brunoeduardodev@users.noreply.github.com) | choco-*: add pt_BR translation (#4868) | 2020-10-28T19:06:39 | [c105fe4d88ab](https://github.com/tldr-pages/tldr/commit/c105fe4d88ab88c28163213bd25cae1fcdfebdc6)

