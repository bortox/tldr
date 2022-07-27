---
author: ['Patrice Denis', 'Srinivasan R', 'Ruben Vereecken', 'rprieto', 'Bruno Bigras']
date: 1617754472
title: "ss, TLDR Pages"
description: "ss, Utility to investigate sockets."
categories: "linux"
---
> More information: <https://manned.org/ss.8>.

- Show all TCP/UDP/RAW/UNIX sockets:

```bash
ss -a -t|-u|-w|-x
```

- Filter TCP sockets by states, only/exclude:

```bash
ss state/exclude bucket/big/connected/synchronized/...
```

- Show all TCP sockets connected to the local HTTPS port (443):

```bash
ss -t src :443
```

- Show all TCP sockets listening on the local 8080 port:

```bash
ss -lt src :8080
```

- Show all TCP sockets along with processes connected to a remote ssh port:

```bash
ss -pt dst :ssh
```

- Show all UDP sockets connected on specific source and destination ports:

```bash
ss -u 'sport == :source_port and dport == :destination_port'
```

- Show all TCP IPv4 sockets locally connected on the subnet 192.168.0.0/16:

```bash
ss -4t src 192.168/16
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | ss: add more info link (#5699) | 2021-04-07T02:14:32 | [8169f4db714f](https://github.com/tldr-pages/tldr/commit/8169f4db714f8bc9240688e22bae074c8897b0c2)
[Bruno Bigras](mailto:bigras.bruno@gmail.com) | ss: add listening socket example (#2853) | 2019-04-19T22:00:53 | [1cef50e33f24](https://github.com/tldr-pages/tldr/commit/1cef50e33f240883bdabea386f32cf3caa20e57c)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Put dashes inside braces for ss command | 2016-01-25T10:52:05 | [02c9d55af454](https://github.com/tldr-pages/tldr/commit/02c9d55af454ad3cd15fae100143bf9842f6f2f7)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Changed ss page to have `-` as option separator | 2016-01-24T23:03:14 | [1a27899c0025](https://github.com/tldr-pages/tldr/commit/1a27899c0025f5fdc2bbcb04762712e8040de990)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Changed ss example to include description for sport | 2016-01-24T18:02:53 | [eb8636d3f01a](https://github.com/tldr-pages/tldr/commit/eb8636d3f01a6113e783a6feac95e0779a4fa1da)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reworked linux ss page | 2016-01-24T16:45:44 | [31c436299f6b](https://github.com/tldr-pages/tldr/commit/31c436299f6b9e99200039df247b1273352df4b6)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Add extra newline between consecutive commands examples. These 6 files had multiple examples all separated by a single newline. While [...] | 2015-10-28T18:10:44 | [2097cf359d9b](https://github.com/tldr-pages/tldr/commit/2097cf359d9bc97448a1dceb5b9549426159ea69)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

