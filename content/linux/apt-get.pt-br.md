---
author: ['Gustavo Dias Alexandre', 'bl-ue', 'Patrice Denis', 'Marco Bonelli']
date: 1618665963
title: "apt-get"
description: "apt-get, Gerenciador de pacotes das distribuições baseadas em Debian."
categories: "linux"
---
> Procure por pacotes utilizando o `apt-cache`.

> Mais informações: <https://manpages.debian.org/latest/apt/apt-get.8.html>.

- Atualizar a lista de pacotes disponíveis (recomenda-se executá-lo antes de outros comandos `apt-get`):

```bash
apt-get update
```

- Instalar um pacote ou atualizá-lo para a versão mais recente:

```bash
apt-get install nome_do_pacote
```

- Remover um pacote:

```bash
apt-get remove nome_do_pacote
```

- Remover um pacote e os seus arquivos de configuração:

```bash
apt-get purge nome_do_pacote
```

- Atualizar todos os pacotes instalados para as versões mais recentes:

```bash
apt-get upgrade
```

- Limpar o repositório local — removendo os arquivos de pacotes (`.deb`) de downloads interrompidos que não podem mais ser baixados:

```bash
apt-get autoclean
```

- Remover todos os pacotes obsoletos:

```bash
apt-get autoremove
```

- Atualizar os pacotes instalados (semelhante ao `upgrade`), porém removendo os obsoletos e instalando pacotes solicitados por novas dependências:

```bash
apt-get dist-upgrade
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Portuguese (Brazil) pages: fix (valid) tldr-lint errors (#5369) | 2021-03-08T20:42:47 | [443568f165ec](https://github.com/tldr-pages/tldr/commit/443568f165eccbfa2521da66158f07e4e9d3bd7a)
[Gustavo Dias Alexandre](mailto:gfdiasa@gmail.com) | apt-get: add autoclean example (#4294) | 2020-09-05T00:46:48 | [6f2b6fc16998](https://github.com/tldr-pages/tldr/commit/6f2b6fc169988e36417f3674c3cf6b079dc2d656)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

