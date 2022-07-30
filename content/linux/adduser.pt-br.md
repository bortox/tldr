---
author: ['Patrice Denis', 'Marco Bonelli']
date: 1618661981
title: "adduser"
description: "adduser, Utilitário para criação de novos usuários."
categories: "linux"
---
> Mais informações: <https://manpages.debian.org/latest/adduser/adduser.html>.

- Criar um novo usuário, o seu diretório na pasta home e solicitar o preenchimento da sua senha:

```bash
adduser nome_do_usuario
```

- Criar um novo usuário sem o seu diretório na pasta home:

```bash
adduser --no-create-home nome_do_usuario
```

- Criar um novo usuário especificando a localização do seu diretório:

```bash
adduser --home caminho_da_pasta_do_usuario nome_do_usuario
```

- Criar um novo usuário e configurar o seu shell de login:

```bash
adduser --shell caminho_para_o_shell nome_do_usuario
```

- Criar um novo usuário e atribuí-lo a um grupo:

```bash
adduser --ingroup grupo nome_do_usuario
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

