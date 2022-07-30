---
author: ['Owen Voke', 'Stig124']
date: 1625841955
title: "authconfig"
description: "authconfig, A CLI interface for configuring system authentication resources."
categories: "linux"
---
> More information: <https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/system-level_authentication_guide/authconfig-install>.

- Display the current configuration (or dry run):

```bash
authconfig --test
```

- Configure the server to use a different password hashing algorithm:

```bash
authconfig --update --passalgo=algorithm
```

- Enable LDAP authentication:

```bash
authconfig --update --enableldapauth
```

- Disable LDAP authentication:

```bash
authconfig --update --disableldapauth
```

- Enable Network Information Service (NIS):

```bash
authconfig --update --enablenis
```

- Enable Kerberos:

```bash
authconfig --update --enablekrb5
```

- Enable Winbind (Active Directory) authentication:

```bash
authconfig --update --enablewinbindauth
```

- Enable local authorization:

```bash
authconfig --update --enablelocauthorize
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Owen Voke](mailto:owzie123@gmail.com) | authconfig: add page (#2007) | 2018-02-22T22:19:44 | [d7cf40e99c45](https://github.com/tldr-pages/tldr/commit/d7cf40e99c4517c0b0792af3635a8c1b220d566e)

