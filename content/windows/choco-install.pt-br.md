---
author: ['Bruno Eduardo de Souza Medeiros', 'Axel Navarro', 'Lucas Gabriel Schneider']
date: 1620501938
title: "choco install"
description: "choco install, Instalar um pacote ou mais com Chocolatey."
categories: "windows"
---
> Mais informações: <https://chocolatey.org/docs/commands-install>.

- Instalar um ou mais pacotes separado por espaço:

```bash
choco install pacote(s)
```

- Instalar pacotes a partir de um aquivo de configuração personalizado:

```bash
choco install caminho/para/pacotes.config
```

- Instalar um arquivo específico `nuspec` ou `nupkg`:

```bash
choco install caminho/para/arquivo
```

- Instalar uma versão específica de um pacote:

```bash
choco install pacote --version versão
```

- Permitir a instalação de múltiplas versões de um pacote:

```bash
choco install pacote --allow-multiple
```

- Confirmar todos prompts automaticamente:

```bash
choco install pacote --yes
```

- Especificar uma fonte personalizada para receber pacotes:

```bash
choco install pacote --source url_do_pacote|apelido
```

- Fornecer um nome e uma senha para autenticação:

```bash
choco install pacote --user usuario --password senha
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | choco-install: normalize caminho para arquivo | 2021-05-08T21:25:38 | [9ced165bacfb](https://github.com/tldr-pages/tldr/commit/9ced165bacfb4e41eec60342aa7399d04f10b115)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Bruno Eduardo de Souza Medeiros](mailto:50559336+brunoeduardodev@users.noreply.github.com) | choco, choco-install, choco-upgrade: add pt_BR translation (#4587) | 2020-10-10T21:38:41 | [6e2e4195b6ca](https://github.com/tldr-pages/tldr/commit/6e2e4195b6cabc330c05c22b026e47dbc7ec3446)

