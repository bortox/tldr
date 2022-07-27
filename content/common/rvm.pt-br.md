---
author: ['Marco Bonelli', 'marchersimon']
date: 1633112881
title: "rvm, TLDR Pages"
description: "rvm, Ferramenta que facilita a instalação e gerenciamento de múltiplas versões da linguagem Ruby."
categories: "common"
---
> Mais informações: <https://rvm.io>.

- Instalar uma ou mais versões separadas por espaço:

```bash
rvm install uma_ou_mais_versoes
```

- Exibir a lista de versões instaladas:

```bash
rvm list
```

- Definir uma versão específica para ser utilizada temporariamente:

```bash
rvm use versao
```

- Definir uma versão específica para ser a instalação padrão:

```bash
rvm --default use versao
```

- Atualizar uma versão já instalada para uma nova versão:

```bash
rvm upgrade versao_atual nova_versao
```

- Remover uma versão mantendo o código fonte:

```bash
rvm uninstall versao
```

- Remover uma versão e o código fonte:

```bash
rvm remove versao
```

- Exibir as dependências específicas para o seu sistema operacional:

```bash
rvm requirements
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

