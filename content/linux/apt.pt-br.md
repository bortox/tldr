---
author: ['Marco Bonelli', 'Patrice Denis']
date: 1618665963
title: "apt, TLDR Pages"
description: "apt, Gerenciador de pacotes das distribuições baseadas em Debian."
categories: "linux"
---
> Mais informações: <https://manpages.debian.org/latest/apt/apt.8.html>.

- Atualizar a lista de pacotes disponíveis (recomenda-se executá-lo antes de outros comandos `apt`):

```bash
sudo apt update
```

- Buscar pacotes correspondentes ao critério de busca:

```bash
apt search criterio_de_busca
```

- Exibir as informações de pacote:

```bash
apt show nome_do_pacote
```

- Instalar um pacote ou atualizá-lo para a versão mais recente:

```bash
sudo apt install nome_do_pacote
```

- Remover um pacote (Para remover os arquivos de configuração deve-se usar a opção `purge` ao invés do `remove`):

```bash
sudo apt remove nome_do_pacote
```

- Atualizar os pacotes instalados para as versões mais recentes:

```bash
sudo apt upgrade
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

