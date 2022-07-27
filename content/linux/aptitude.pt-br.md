---
author: ['Marco Bonelli', 'Patrice Denis', 'bl-ue']
date: 1618665963
title: "aptitude, TLDR Pages"
description: "aptitude, Gerenciador de pacotes das distribuições baseadas em Debian."
categories: "linux"
---
> Mais informações: <https://manpages.debian.org/latest/aptitude/aptitude.8.html>.

- Atualizar a lista de pacotes disponíveis (recomenda-se executá-lo antes de outros comandos `aptitude`):

```bash
aptitude update
```

- Instalar um novo pacote e suas dependências:

```bash
aptitude install nome_do_pacote
```

- Buscar pacotes correspondentes ao critério de busca:

```bash
aptitude search criterio_de_busca
```

- Remover um pacote e todos que dependam dele:

```bash
aptitude remove nome_do_pacote
```

- Atualizar os pacotes instalados para as versões mais recentes:

```bash
aptitude upgrade
```

- Atualizar os pacotes instalados (semelhante ao `upgrade`), porém removendo os obsoletos e instalando pacotes solicitados por novas dependências:

```bash
aptitude full-upgrade
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

