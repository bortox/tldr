---
author: ['Juri']
date: 1634764911
title: "ipaggcreate, TLDR Pages"
description: "ipaggcreate, Produce aggregate statistics of TCP/IP dumps."
categories: "common"
---
> More information: <https://manned.org/ipaggcreate>.

- Count the number of packets sent from each source address appearing in a pcap file:

```bash
ipaggcreate --src path/to/file.pcap
```

- Group and count packets read from a network interface by IP packet length:

```bash
ipaggcreate --interface eth0 --length
```

- Count the number of bytes sent between each address pair appearing in a pcap file:

```bash
ipaggcreate --address-pairs --bytes path/to/file.pcap
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | ipsumdump, ipaggcreate, ipaggmanip: add page (#6966) | 2021-10-20T23:21:51 | [e26d7c6659fd](https://github.com/tldr-pages/tldr/commit/e26d7c6659fdd1a2ddd9dcf0d57c95eaa4615f94)

