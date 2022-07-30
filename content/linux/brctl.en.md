---
author: ['Stig124', 'Seth Falco', 'Marco Bonelli']
date: 1629050349
title: "brctl"
description: "brctl, Ethernet bridge administration."
categories: "linux"
---
> More information: <https://manned.org/brctl>.

- Show a list with information about currently existing Ethernet bridges:

```bash
sudo brctl show
```

- Create a new Ethernet bridge interface:

```bash
sudo brctl add bridge_name
```

- Delete an existing Ethernet bridge interface:

```bash
sudo brctl del bridge_name
```

- Add an interface to an existing bridge:

```bash
sudo brctl addif bridge_name interface_name
```

- Remove an interface from an existing bridge:

```bash
sudo brctl delif bridge_name interface_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | brctl: add page. | 2019-01-11T01:53:19 | [ac5cd6d896a4](https://github.com/tldr-pages/tldr/commit/ac5cd6d896a449f8ea6144c932d610781e373877)

