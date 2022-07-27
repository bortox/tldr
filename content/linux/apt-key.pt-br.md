---
author: ['Marco Bonelli', 'Patrice Denis']
date: 1618665963
title: "apt-key, TLDR Pages"
description: "apt-key, Gerenciador de chaves utilizado pelo gerenciador de pacotes APT nas distribuições baseadas em Debian."
categories: "linux"
---
> Mais informações: <https://manpages.debian.org/latest/apt/apt-key.8.html>.

- Exibir as chaves confiáveis:

```bash
apt-key list
```

- Adicionar uma chave na lista de chaves confiáveis:

```bash
apt-key add arquivo_da_chave_publica.asc
```

- Remover uma chave da lista de chaves confiáveis:

```bash
apt-key del key_id
```

- Adicionar uma chave remota na lista de chaves confiáveis:

```bash
wget -qO - https://host.tld/arquivo.key | apt-key add -
```

- Adicionar uma chave, de um servidor de chaves, na lista de chaves confiáveis:

```bash
apt-key adv --keyserver pgp.mit.edu --recv KEYID
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | apt-*: add more info links; apt-file: add regex search example (#5710) | 2021-04-17T15:26:03 | [ca8394dc52de](https://github.com/tldr-pages/tldr/commit/ca8394dc52def4e55971ce4049b20fa8839f464d)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

