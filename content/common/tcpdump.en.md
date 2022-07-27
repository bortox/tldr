---
author: ['Srinivasan R', 'egilkh', 'Marco Bonelli', 'Ruben Vereecken', 'Agniva De Sarker', 'pxgamer', 'James H. Linder', 'Ming Chen', 'rprieto', 'Clayton Sayer']
date: 1600794584
title: "tcpdump, TLDR Pages"
description: "tcpdump, Dump traffic on a network."
categories: "common"
---
> More information: <https://www.tcpdump.org>.

- List available network interfaces:

```bash
tcpdump -D
```

- Capture the traffic of a specific interface:

```bash
tcpdump -i eth0
```

- Capture all TCP traffic showing contents (ASCII) in console:

```bash
tcpdump -A tcp
```

- Capture the traffic from or to a host:

```bash
tcpdump host www.example.com
```

- Capture the traffic from a specific interface, source, destination and destination port:

```bash
tcpdump -i eth0 src 192.168.1.1 and dst 192.168.1.2 and dst port 80
```

- Capture the traffic of a network:

```bash
tcpdump net 192.168.1.0/24
```

- Capture all traffic except traffic over port 22 and save to a dump file:

```bash
tcpdump -w dumpfile.pcap port not 22
```

- Read from a given dump file:

```bash
tcpdump -r dumpfile.pcap
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Clayton Sayer](mailto:31869154+clayton-sayer-hs@users.noreply.github.com) | tcpdump: fixed negation example (#4346) | 2020-09-22T19:09:44 | [f4ae3099c8c2](https://github.com/tldr-pages/tldr/commit/f4ae3099c8c22661932e274ef9e88b8e783ebabc)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | tcpdump: add link to homepage | 2019-05-14T19:58:59 | [a86fc0d2a564](https://github.com/tldr-pages/tldr/commit/a86fc0d2a564a9b54a1bc0ebf9d3dd9b388bab79)
[Ming Chen](mailto:mingchen@users.noreply.github.com) | tcpdump: Add {{}} token to command arguments. | 2017-12-04T22:43:33 | [1ba5e9aa1575](https://github.com/tldr-pages/tldr/commit/1ba5e9aa1575928eb907bbaf11482f3ef6c4e675)
[Ming Chen](mailto:mingchen@users.noreply.github.com) | Add -D and -r from tcpdump | 2017-12-03T17:22:45 | [eb7224387bf6](https://github.com/tldr-pages/tldr/commit/eb7224387bf6dacbaa99d8d38f3aecc79b18c7e9)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | tcpdump: fixed syntax error and added better params | 2016-01-06T18:00:53 | [3e355c7f366a](https://github.com/tldr-pages/tldr/commit/3e355c7f366a8bbffc1bb32613e08591b54b15c5)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[egilkh](mailto:egilkh@gmail.com) | Remove date from tcpdump example. | 2014-08-18T11:04:06 | [facb34a60fd4](https://github.com/tldr-pages/tldr/commit/facb34a60fd419255bd87040912f912f59e3975a)
[egilkh](mailto:egilkh@gmail.com) | Make tcpdump, wall and useradd match formatting. | 2014-08-18T08:22:39 | [6ebb0b550b1b](https://github.com/tldr-pages/tldr/commit/6ebb0b550b1b4c430bc47c0f91f02bee996bdcad)
[James H. Linder](mailto:james@jlinder.com) | tcpdump command to output to a dated filename all traffic not on port 22 | 2014-03-27T19:46:32 | [133a8cc13faa](https://github.com/tldr-pages/tldr/commit/133a8cc13faa73de55c9692a433c8b97e9ca342a)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

