---
author: ['Waldir Pimenta', 'Ruben Vereecken', 'Nikhil Sonti', 'lincc', 'Seth Falco']
date: 1629050349
title: "ifconfig, TLDR Pages"
description: "ifconfig, Network Interface Configurator."
categories: "common"
---
> More information: <https://net-tools.sourceforge.io/man/ifconfig.8.html>.

- View network settings of an Ethernet adapter:

```bash
ifconfig eth0
```

- Display details of all interfaces, including disabled interfaces:

```bash
ifconfig -a
```

- Disable eth0 interface:

```bash
ifconfig eth0 down
```

- Enable eth0 interface:

```bash
ifconfig eth0 up
```

- Assign IP address to eth0 interface:

```bash
ifconfig eth0 ip_address
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | ifconfig: add more information link (#6218) Co-authored-by: Muhammad Falak R Wani <falakreyaz@gmail.com> Co-authored-by: CleanMachine1 [...] | 2021-07-12T08:51:22 | [03e2e3389e47](https://github.com/tldr-pages/tldr/commit/03e2e3389e47edab092e1336c704fc5f5f2b7ba6)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fix descriptions split by mistake in #633 (#1098) | 2016-10-12T17:58:04 | [c15d705d4007](https://github.com/tldr-pages/tldr/commit/c15d705d4007cc9adfa737a0ec6b88bef56656a8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Nikhil Sonti](mailto:nikhilsv92@gmail.com) | ifconfig.md: Adding ifconfig command | 2015-12-29T11:18:12 | [0492cadd23aa](https://github.com/tldr-pages/tldr/commit/0492cadd23aa7258f0799b4d2e130705a66eaac0)

