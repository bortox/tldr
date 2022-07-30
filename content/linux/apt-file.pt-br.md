---
author: ['Patrice Denis', 'Marco Bonelli']
date: 1618665963
title: "apt-file"
description: "apt-file, Buscador de arquivos nos pacotes apt, incluindo os não instalados."
categories: "linux"
---
> Mais informações: <https://manpages.debian.org/latest/apt-file/apt-file.1.html>.

- Atualizar as informações dos pacotes a partir de todos os repositórios remotos:

```bash
sudo apt update
```

- Buscar por pacotes que contêm o arquivo ou caminho especificado:

```bash
apt-file search nome_do_pacote_ou_caminho
```

- Listar o conteúdo de um pacote específico:

```bash
apt-file list nome_do_pacote
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

