---
author: ['Lukáš Zapletal', 'Ruben Vereecken', 'Stig124', 'Don Mayo', 'Lucas Gabriel Schneider', 'bl-ue']
date: 1625841955
title: "firewall-cmd, TLDR Pages"
description: "firewall-cmd, The firewalld command-line client."
categories: "linux"
---
> More information: <https://firewalld.org/documentation/man-pages/firewall-cmd>.

- View the available firewall zones:

```bash
firewall-cmd --get-active-zones
```

- View the rules which are currently applied:

```bash
firewall-cmd --list-all
```

- Permanently move the interface into the block zone, effectively blocking all communication:

```bash
firewall-cmd --permanent --zone=block --change-interface=enp1s0
```

- Permanently open the port for a service in the specified zone (like port 443 when in the `public` zone):

```bash
firewall-cmd --permanent --zone=public --add-service=https
```

- Permanently close the port for a service in the specified zone (like port 80 when in the `public` zone):

```bash
firewall-cmd --permanent --zone=public --remove-service=http
```

- Permanently open two arbitrary ports in the specified zone:

```bash
firewall-cmd --permanent --zone=public --add-port=25565/tcp --add-port=19132/udp
```

- Reload firewalld to force rule changes to take effect:

```bash
firewall-cmd --reload
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Lukáš Zapletal](mailto:lzap@redhat.com) | firewall-cmd: add zone change and arbitrary ports (#3815) | 2020-03-03T18:21:21 | [c3eb93f17475](https://github.com/tldr-pages/tldr/commit/c3eb93f17475521fdb45698f419e90270d294f18)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Don Mayo](mailto:don.mayo@oracle.com) | Add page for firewall-cmd in linux | 2015-01-12T16:45:34 | [bd28888d6535](https://github.com/tldr-pages/tldr/commit/bd28888d653549c5160978357341a2eb20afcbec)

