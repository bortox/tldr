---
author: ['Jeremy Hettenhouser', 'bl-ue', 'Adam Herst', 'Muhammad Falak R Wani']
date: 1640996972
title: "ethtool"
description: "ethtool, Display and modify Network Interface Controller (NIC) parameters."
categories: "linux"
---
> More information: <http://man7.org/linux/man-pages/man8/ethtool.8.html>.

- Display the current settings for an interface:

```bash
ethtool eth0
```

- Display the driver information for an interface:

```bash
ethtool --driver eth0
```

- Display all supported features for an interface:

```bash
ethtool --show-features eth0
```

- Display the network usage statistics for an interface:

```bash
ethtool --statistics eth0
```

- Blink one or more LEDs on an interface for 10 seconds:

```bash
ethtool --identify eth0 10
```

- Set the link speed, duplex mode, and parameter auto-negotiation for a given interface:

```bash
ethtool -s eth0 speed 10|100|1000 duplex half|full autoneg on|off
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | ethtool: add example to show all features (#7590) | 2022-01-01T01:29:32 | [ef8fb5783906](https://github.com/tldr-pages/tldr/commit/ef8fb57839069cbed5a7eeb28de2f96141be6033)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Adam Herst](mailto:adamherst@adamherst.com) | ethtool: add examples (#5307) | 2021-02-24T17:30:45 | [4364446e1739](https://github.com/tldr-pages/tldr/commit/4364446e1739763de8845eaa21dbd0bb4a0fa281)
[Jeremy Hettenhouser](mailto:jhettenh@gmail.com) | ethtool: add page (#3508) | 2019-11-01T00:33:56 | [5d9e9727a01a](https://github.com/tldr-pages/tldr/commit/5d9e9727a01a6ebe9f7c854fcefa66f2d0bd3c53)

