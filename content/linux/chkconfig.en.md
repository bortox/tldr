---
author: ['Stig124', 'Tung Ha']
date: 1625841955
title: "chkconfig, TLDR Pages"
description: "chkconfig, Manage the runlevel of services on CentOS 6."
categories: "linux"
---
> More information: <https://manned.org/chkconfig>.

- List services with runlevel:

```bash
chkconfig --list
```

- Show a service's runlevel:

```bash
chkconfig --list ntpd
```

- Enable service at boot:

```bash
chkconfig sshd on
```

- Enable service at boot for runlevels 2, 3, 4, and 5:

```bash
chkconfig --level 2345 sshd on
```

- Disable service at boot:

```bash
chkconfig ntpd off
```

- Disable service at boot for runlevel 3:

```bash
chkconfig --level 3 ntpd off
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Tung Ha](mailto:tunght13488@users.noreply.github.com) | chkconfig: add page (#2217) | 2018-07-29T00:17:58 | [d432ed3c3929](https://github.com/tldr-pages/tldr/commit/d432ed3c39293b2929127fa09fd366bb468c2cab)

