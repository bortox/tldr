---
author: ['rprieto', 'Ruben Vereecken', 'Sadeed', 'Zachariah Kendall']
date: 1635014706
title: "traceroute, TLDR Pages"
description: "traceroute, Print the route packets trace to network host."
categories: "common"
---
> More information: <https://manned.org/traceroute>.

- Traceroute to a host:

```bash
traceroute host
```

- Disable IP address and host name mapping:

```bash
traceroute -n host
```

- Specify wait time for response:

```bash
traceroute -w 0.5 host
```

- Specify number of queries per hop:

```bash
traceroute -q 5 host
```

- Specify size in bytes of probing packet:

```bash
traceroute host 42
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | task, telnet, tldrl, tput, traceroute, transcode, type: add link (#7038) | 2021-10-23T20:45:06 | [81dc4a1e8016](https://github.com/tldr-pages/tldr/commit/81dc4a1e8016c5621134ebf80724be7d7d67c56a)
[Zachariah Kendall](mailto:zachariahkendall@gmail.com) | traceroute: Add example of specifying datagram size (#999) | 2016-08-21T21:07:22 | [6e25c3cfb9cc](https://github.com/tldr-pages/tldr/commit/6e25c3cfb9ccf5be013986b428760e91fca2bbbe)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

