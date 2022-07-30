---
author: ['Axel Navarro', 'Stig124', 'Marco Bonelli']
date: 1632142761
title: "chage"
description: "chage, Gerencia informações de expiração de conta e senha do usuário."
categories: "linux"
---
> Mais informações: <https://manned.org/chage>.

- Exibir as informações referentes a senha do usuário:

```bash
chage --list nome_do_usuario
```

- Habilitar a expiração da senha do usuário em 10 dias:

```bash
sudo chage --maxdays 10 nome_do_usuario
```

- Desabilitar a expiração da senha do usuário:

```bash
sudo chage --maxdays -1 nome_do_usuario
```

- Definir a data de expiração da conta do usuário:

```bash
sudo chage --expiredate YYYY-MM-DD nome_do_usuario
```

- Obrigar o usuário a alterar sua senha no próximo login:

```bash
sudo chage --lastday 0 nome_do_usuario
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | chage: fix examples and use long arguments (#6541) | 2021-09-20T14:59:21 | [61da0633dea9](https://github.com/tldr-pages/tldr/commit/61da0633dea9e2d5f0235a82d86351bf1d11e664)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

