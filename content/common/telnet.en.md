---
author: ['Waldir Pimenta', 'Matías Andrade Guzmán', 'Tan A', 'rprieto', 'Sadeed', 'Ruben Vereecken']
date: 1635014706
title: "telnet"
description: "telnet, Connect to a specified port of a host using the telnet protocol."
categories: "common"
---
> More information: <https://manned.org/telnet>.

- Telnet to the default port of a host:

```bash
telnet host
```

- Telnet to a specific port of a host:

```bash
telnet ip_address port
```

- Exit a telnet session:

```bash
quit
```

- Emit the default escape character combination for terminating the session:

```bash
Ctrl + ]
```

- Start telnet with "x" as the session termination character:

```bash
telnet -e x ip_address port
```

- Telnet to Star Wars animation:

```bash
telnet towel.blinkenlights.nl
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | task, telnet, tldrl, tput, traceroute, transcode, type: add link (#7038) | 2021-10-23T20:45:06 | [81dc4a1e8016](https://github.com/tldr-pages/tldr/commit/81dc4a1e8016c5621134ebf80724be7d7d67c56a)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | telnet: add Star Wars ASCII animation example (#5323) | 2021-03-03T12:56:40 | [0ea2adae0998](https://github.com/tldr-pages/tldr/commit/0ea2adae099881ef950bc5bc16d2d0ea20bf4dc9)
[Matías Andrade Guzmán](mailto:mandrade2@uc.cl) | telnet: fix typo Line 7 said telnel instead of telnet. | 2017-11-19T05:42:10 | [f853a5956ebf](https://github.com/tldr-pages/tldr/commit/f853a5956ebf29c39cec973d16fbbb1557993032)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | telnet: improve descriptions (#1353) * telnet: improve descriptions also format "x" as a token in the last example. * telnet: update [...] | 2017-05-04T21:50:30 | [c9063d15b944](https://github.com/tldr-pages/tldr/commit/c9063d15b94451100df980be7934e433ba9b0959)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Telnet's syntax was wrong | 2016-01-13T11:12:44 | [c9d0ed3e16e4](https://github.com/tldr-pages/tldr/commit/c9d0ed3e16e449eabbe63d248eda9782d0a0ac8f)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

