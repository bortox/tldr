---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider']
date: 1570455110
title: "bundle, TLDR Pages"
description: "bundle, Gerenciador de dependências da linguagem de programação Ruby."
categories: "common"
---
> Mais informações: <https://bundler.io/man/bundle.1.html>.

- Instalar todas as gemas definidas no `Gemfile`:

```bash
bundle install
```

- Atualizar todas as gemas, respeitando as regras definidas no `Gemfile`, e recriar o arquivo `Gemfile.lock`:

```bash
bundle update
```

- Atualizar uma gema específica definida no `Gemfile`:

```bash
bundle update --source nome_da_gema
```

- Criar o esqueleto do projeto de uma nova gema:

```bash
bundle gem nome_da_gema
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages (pt_BR): fix homepage tokens (#3340) | 2019-10-07T15:31:50 | [83b623d988f7](https://github.com/tldr-pages/tldr/commit/83b623d988f7940581b5e9fbd43ec0fdc7496a68)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

