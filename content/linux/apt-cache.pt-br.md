---
author: ['Marco Bonelli', 'Patrice Denis']
date: 1618665963
title: "apt-cache, TLDR Pages"
description: "apt-cache, Buscador de pacotes para distribuições baseadas no Debian."
categories: "linux"
---
> Mais informações: <https://manpages.debian.org/latest/apt/apt-cache.8.html>.

- Buscar pacotes, no cache de pacotes APT, correspondentes ao critério de busca:

```bash
apt-cache search criterio_de_busca
```

- Exibir informações sobre um pacote:

```bash
apt-cache show nome_do_pacote
```

- Informar a situação de um pacote, se ele está instalado e atualizado:

```bash
apt-cache policy nome_do_pacote
```

- Exibir as dependências de um pacote:

```bash
apt-cache depends nome_do_pacote
```

- Exibir pacotes dependentes de um determinado pacote:

```bash
apt-cache rdepends nome_do_pacote
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

