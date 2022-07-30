---
author: ['Felix Yan', 'Justin Kenyon', 'rprieto', 'lord63', 'Eckl, Máté', 'Ruben Vereecken', 'Patrice Denis', 'Seth Falco', 'marchersimon']
date: 1631521281
title: "ip"
description: "ip, Show / manipulate routing, devices, policy routing and tunnels."
categories: "linux"
---
> Some subcommands such as `ip address` have their own usage documentation.

> More information: <https://www.man7.org/linux/man-pages/man8/ip.8.html>.

- List interfaces with detailed info:

```bash
ip address
```

- List interfaces with brief network layer info:

```bash
ip -brief address
```

- List interfaces with brief link layer info:

```bash
ip -brief link
```

- Display the routing table:

```bash
ip route
```

- Show neighbors (ARP table):

```bash
ip neighbour
```

- Make an interface up/down:

```bash
ip link set interface up/down
```

- Add/Delete an IP address to an interface:

```bash
ip addr add/del ip/mask dev interface
```

- Add a default route:

```bash
ip route add default via ip dev interface
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Patrice Denis](mailto:patrice.denis@gmail.com) | at, ifdown, ifup, ip-address, ip: add French translation (#5505) | 2021-03-27T12:51:16 | [170f5f9ebcfc](https://github.com/tldr-pages/tldr/commit/170f5f9ebcfca1427d1f70e33387134c09795552)
[Eckl, Máté](mailto:ecklm94@gmail.com) | ip: add brief listing examples (#4352) | 2020-10-06T13:12:54 | [34bd24fc7bec](https://github.com/tldr-pages/tldr/commit/34bd24fc7bec987ac460b3b33dc601253cfb4eb2)
[Felix Yan](mailto:felixonmars@archlinux.org) | ip: add an example for neighbors (#2197) | 2018-07-16T17:00:02 | [ae8a46a3e2fe](https://github.com/tldr-pages/tldr/commit/ae8a46a3e2feec39c835aaba8e99e1c852c95ec8)
[Justin Kenyon](mailto:kenyonj@gmail.com) | Update grammar `a` should be used instead of `an` in this context. | 2017-04-03T17:00:15 | [3a858a93afa3](https://github.com/tldr-pages/tldr/commit/3a858a93afa3b52bfd77406380560a9709467d3d)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix markdown lint warning for linux man pages | 2015-10-22T09:00:05 | [1d2d523b2138](https://github.com/tldr-pages/tldr/commit/1d2d523b21388c959e70b5037641b57b9e50a39a)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

