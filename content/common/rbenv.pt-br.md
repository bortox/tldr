---
author: ['Marco Bonelli', 'marchersimon']
date: 1633112881
title: "rbenv, TLDR Pages"
description: "rbenv, Ferramenta que facilita a instalação e gerenciamento de múltiplas versões da linguagem Ruby."
categories: "common"
---
> Mais informações: <https://github.com/rbenv/rbenv>.

- Instalar uma ou mais versões, separadas por espaço:

```bash
rbenv install uma_ou_mais_versoes
```

- Exibir a lista de versões instaladas:

```bash
rbenv versions
```

- Determinar uma versão específica para ser a instalação padrão:

```bash
rbenv global versao
```

- Determinar uma versão específica para um projeto. Este comando deve ser executado no diretório do projeto:

```bash
rbenv local versao
```

- Exibir a versão ativa:

```bash
rbenv version
```

- Remover uma versão:

```bash
rbenv uninstall versao
```

- Exibir todas as versões que contém um determinado executável:

```bash
rbenv whence executavel
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

