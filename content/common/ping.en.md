---
author: ['David Pavlík', 'Felix Yan', 'Peter Tripp', 'rprieto', 'Starbeamrainbowlabs', 'syleung', 'Ruben Vereecken']
date: 1633517967
title: "ping"
description: "ping, Send ICMP ECHO_REQUEST packets to network hosts."
categories: "common"
---
> More information: <https://manned.org/ping>.

- Ping host:

```bash
ping host
```

- Ping a host only a specific number of times:

```bash
ping -c count host
```

- Ping host, specifying the interval in seconds between requests (default is 1 second):

```bash
ping -i seconds host
```

- Ping host without trying to lookup symbolic names for addresses:

```bash
ping -n host
```

- Ping host and ring the bell when a packet is received (if your terminal supports it):

```bash
ping -a host
```

- Also display a message if no response was received:

```bash
ping -O host
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | ping, ping6: add more information link (#6658) | 2021-10-06T12:59:27 | [4efa36e763c9](https://github.com/tldr-pages/tldr/commit/4efa36e763c9485e45704136ac7c588b350e6657)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | ping: add -O example (#2203) | 2018-07-19T14:56:58 | [32d72902c8cc](https://github.com/tldr-pages/tldr/commit/32d72902c8cc7b0ee964452c26b139cc9a34c11e)
[David Pavlík](mailto:pavlik.d@seznam.cz) | ping: add -a example (#1027) | 2016-09-23T16:47:43 | [c49289b4a75f](https://github.com/tldr-pages/tldr/commit/c49289b4a75f7fb45c614cb0ecbe237afca767ac)
[Peter Tripp](mailto:petertripp@gmail.com) | Fix ping, zfs and zpool to match current style guide. | 2016-01-16T20:45:16 | [c6635ec81549](https://github.com/tldr-pages/tldr/commit/c6635ec8154918099af4fc5f4fbf2a7d9b12f112)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Felix Yan](mailto:felixonmars@gmail.com) | ping page: add -n param | 2014-07-23T17:50:33 | [add98df98ef4](https://github.com/tldr-pages/tldr/commit/add98df98ef487313c966070822cff7288a4540c)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

