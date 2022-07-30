---
author: ['Stig124', 'Marco Bonelli']
date: 1625841955
title: "authconfig"
description: "authconfig, Interface de linha comandos para configurar o sistema de autenticação."
categories: "linux"
---
> Mais informações: <https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/system-level_authentication_guide/authconfig-install>.

- Exibir as configurações atuais (ou dry run):

```bash
authconfig --test
```

- Configurar o servidor para utilizar diferentes algoritmos de hash para as senhas:

```bash
authconfig --update --passalgo=algoritmo
```

- Habilitar a autenticação via LDAP:

```bash
authconfig --update --enableldapauth
```

- Desabilitar a autenticação via LDAP:

```bash
authconfig --update --disableldapauth
```

- Habilitar o Network Information Service (NIS):

```bash
authconfig --update --enablenis
```

- Habilitar Kerberos:

```bash
authconfig --update --enablekrb5
```

- Habilitar a autenticação Winbind (Active Directory):

```bash
authconfig --update --enablewinbindauth
```

- Habilitar a autorização local:

```bash
authconfig --update --enablelocauthorize
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

