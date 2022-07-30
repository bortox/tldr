---
author: ['Patrice Denis', 'Marco Bonelli']
date: 1618665963
title: "apt-mark"
description: "apt-mark, Utilitário que altera as configurações dos pacotes instalados."
categories: "linux"
---
> Mais informações: <https://manpages.debian.org/latest/apt/apt-mark.8.html>.

- Marcar um pacote como instalado automaticamente:

```bash
sudo apt-mark auto nome_do_pacote
```

- Bloquear um pacote na sua versão atual, impedindo que ele seja atualizado:

```bash
sudo apt-mark hold nome_do_pacote
```

- Desbloquear um pacote, permitindo que ele seja atualizado:

```bash
sudo apt-mark unhold nome_do_pacote
```

- Listar os pacotes instalados manualmente:

```bash
apt-mark showmanual
```

- Listar os pacotes bloqueados:

```bash
apt-mark showhold
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

