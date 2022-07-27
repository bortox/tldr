---
author: ['Marco Bonelli', 'Stig124']
date: 1625841955
title: "chkconfig, TLDR Pages"
description: "chkconfig, Gerencia o runlevel dos serviços no CentOS 6."
categories: "linux"
---
> Mais informações: <https://manned.org/chkconfig>.

- Exibir os serviços com os respectivos runlevels:

```bash
chkconfig --list
```

- Exibir o runlevel de um serviço:

```bash
chkconfig --list ntpd
```

- Habilitar o início de um serviço durante o processo de boot:

```bash
chkconfig sshd on
```

- Habilitar o início do serviço durante o processo de boot para os runlevels 2, 3, 4 e 5:

```bash
chkconfig --level 2345 sshd on
```

- Desabilitar a inicialização de um determinado serviço durante o processo de boot:

```bash
chkconfig ntpd off
```

- Desabilitar a inicialização de um determinado serviço durante o processo de boot para o runlevel 3:

```bash
chkconfig --level 3 ntpd off
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

