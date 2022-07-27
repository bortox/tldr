---
author: ['Iván Hernández Cazorla', 'Nick Smyrnioudis', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "iwconfig, TLDR Pages"
description: "iwconfig, Configure and show the parameters of a wireless network interface."
categories: "linux"
---
> More information: <https://manned.org/iwconfig>.

- Show the parameters and statistics of all the interfaces:

```bash
iwconfig
```

- Show the parameters and statistics of the specified interface:

```bash
iwconfig interface
```

- Set the ESSID (network name) of the specified interface (e.g. eth0 or wlp2s0):

```bash
iwconfig interface new_network_name
```

- Set the operating mode of the specified interface:

```bash
iwconfig interface mode ad hoc|Managed|Master|Repeater|Secondary|Monitor|Auto
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Nick Smyrnioudis](mailto:32795986+NickSmyr@users.noreply.github.com) | iwconfig : fix error in last example (#4791) changed ifconfig to iwconfig | 2020-10-24T14:37:55 | [811b360cb4db](https://github.com/tldr-pages/tldr/commit/811b360cb4db3584a01c4bdbe1bf72dd830f2fac)
[Iván Hernández Cazorla](mailto:ivan@ivanhercaz.com) | iwconfig: add page (#3789) | 2020-01-25T13:36:45 | [88fb3b21a8d6](https://github.com/tldr-pages/tldr/commit/88fb3b21a8d6e48cc3bdb780b0f3fae6ca691f4a)

