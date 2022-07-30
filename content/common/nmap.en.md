---
author: ['Tom Dörr', 'Jacek Wielemborek', 'Matthew Wo', 'Fazle Arefin', 'rprieto', 'Henry Vindin', 'Ray Voice', 'Dave', 'Starbeamrainbowlabs', 'Marco Bonelli', 'bl-ue', 'Ruben Vereecken']
date: 1656453409
title: "nmap"
description: "nmap, Network exploration tool and security / port scanner."
categories: "common"
---
> Some features only activate when Nmap is run with root privileges.

> More information: <https://nmap.org>.

- Check if an IP address is up, and guess the remote host's operating system:

```bash
nmap -O ip_or_hostname
```

- Try to determine whether the specified hosts are up (ping scan) and what their names are:

```bash
nmap -sn ip_or_hostname optional_another_address
```

- Also enable scripts, service detection, OS fingerprinting and traceroute:

```bash
nmap -A address_or_addresses
```

- Scan a specific list of ports (use '-p-' for all ports from 1 to 65535):

```bash
nmap -p port1,port2,...,portN address_or_addresses
```

- Perform service and version detection of the top 1000 ports using default NSE scripts; writing results ('-oN') to output file:

```bash
nmap -sC -sV -oN top-1000-ports.txt address_or_addresses
```

- Scan target(s) carefully using 'default and safe' NSE scripts:

```bash
nmap --script "default and safe" address_or_addresses
```

- Scan web server running on standard ports 80 and 443 using all available 'http-*' NSE scripts:

```bash
nmap --script "http-*" address_or_addresses -p 80,443
```

- Perform a stealthy very slow scan ('-T0') trying to avoid detection by IDS/IPS and use decoy ('-D') source IP addresses:

```bash
nmap -T0 -D decoy1_ipaddress,decoy2_ipaddress,...,decoyN_ipaddress address_or_addresses
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Fazle Arefin](mailto:fazlearefin@users.noreply.github.com) | nmap: update examples to be more practical and useful (#8099) | 2022-06-28T23:56:49 | [f5348d25a4b8](https://github.com/tldr-pages/tldr/commit/f5348d25a4b8822b62b048d424fc3dfd8c44c1f3)
[Tom Dörr](mailto:tomdoerr96@gmail.com) | Fix sentence (#6272) | 2021-07-28T16:19:23 | [ae695a28b9b5](https://github.com/tldr-pages/tldr/commit/ae695a28b9b55e0e1fc7b84187a16acdb4d76700)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | nmap: put command flags in example descriptions in backticks (#5812) | 2021-04-22T22:06:36 | [43901df7ecde](https://github.com/tldr-pages/tldr/commit/43901df7ecde69084a69fc82df6c77a314ab53b9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | nmap: remove SSL example to reduce count to 8 | 2021-01-04T01:49:11 | [12ec154efb35](https://github.com/tldr-pages/tldr/commit/12ec154efb35a637ee59c313cf2f68d192f782d5)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Dave](mailto:12233528+kawaiipantsu@users.noreply.github.com) | nmap: add full nse scan example (#4480) | 2020-10-15T00:29:25 | [69413c2aa27e](https://github.com/tldr-pages/tldr/commit/69413c2aa27ee05734d869e0d5da4e6829185ed6)
[Ray Voice](mailto:33094591+Ray6464@users.noreply.github.com) | nmap: add -O example (#4400) | 2020-10-14T15:46:17 | [8afd5f9445ad](https://github.com/tldr-pages/tldr/commit/8afd5f9445ad0688d6ac63f708562e0ac4df1abc)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | nmap, pdftk, samtools, tig: ellipsis consistency. | 2019-02-03T04:27:37 | [1799a53d7876](https://github.com/tldr-pages/tldr/commit/1799a53d7876f1abb9ddcd1eb33cd2ca6df745ca)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: fix syntax | 2019-02-03T01:28:36 | [334c0b4fa3ea](https://github.com/tldr-pages/tldr/commit/334c0b4fa3ea6f24c50d62061db9075125cc608b)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | nmap: add homepage | 2019-02-03T01:28:36 | [162c2bfb5c93](https://github.com/tldr-pages/tldr/commit/162c2bfb5c930e198d6d0ca1d74c439d44994caa)
[Henry Vindin](mailto:henry@hcv.ind.in) | remove generic nse example as its probably man page material, not tldr | 2017-10-26T05:42:50 | [67314d854880](https://github.com/tldr-pages/tldr/commit/67314d85488073abfa1e686b51409309cef0d16a)
[Henry Vindin](mailto:hvindin@westpac.com.au) | Add more examples for nmap for common activities such as: - scanning a host with nse scripts - scanning enabled SSL/TLS [...] | 2017-10-26T05:42:50 | [ee0486e7f293](https://github.com/tldr-pages/tldr/commit/ee0486e7f293bbd6cf1bdb925345eb40e6e15942)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted nmap | 2016-01-21T13:21:22 | [c1f7204e377f](https://github.com/tldr-pages/tldr/commit/c1f7204e377f9848facf1d5d7945bf3470fcbfa6)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Merge branch 'patch-1' of git://github.com/d33tah/tldr into d33tah-patch-1 Conflicts: pages/common/nmap.md | 2016-01-21T13:21:11 | [807c8d91d94a](https://github.com/tldr-pages/tldr/commit/807c8d91d94ac37ea92a30ca2004d965cabcdd4e)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Jacek Wielemborek](mailto:d33tah@gmail.com) | Fix interpunction, mention scripts in -A. | 2015-12-31T13:55:20 | [68beb5eb8ea4](https://github.com/tldr-pages/tldr/commit/68beb5eb8ea4f864d10742590b2cf99aeeee0935)
[Jacek Wielemborek](mailto:d33tah@gmail.com) | Update nmap.md. | 2015-12-31T09:07:00 | [b6ca634bb1e7](https://github.com/tldr-pages/tldr/commit/b6ca634bb1e7511fa18517fa6549db9764fd0ce1)
[Matthew Wo](mailto:9029537@gmail.com) | added fast scan for nmap | 2015-12-29T15:30:36 | [b48497fdeeab](https://github.com/tldr-pages/tldr/commit/b48497fdeeab0304480d79451d52820bce36a834)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

