---
author: ['Juri']
date: 1634764911
title: "ipsumdump"
description: "ipsumdump, Summarise TCP/IP dumps into a human and machine readable ASCII format."
categories: "common"
---
> More information: <https://manned.org/ipsumdump>.

- Print the source and destination IP addresses of all packets in a pcap file:

```bash
ipsumdump --src --dst path/to/file.pcap
```

- Print the timestamps, source address, source port, destination address, destination port and protocol of all packets read from a given network interface:

```bash
ipsumdump --interface eth0 -tsSdDp
```

- Print the anonymised source address, anonymised destination address, and IP packet length of all packets in a pcap file:

```bash
ipsumdump --src --dst --length --anonymize path/to/file.pcap
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | ipsumdump, ipaggcreate, ipaggmanip: add page (#6966) | 2021-10-20T23:21:51 | [e26d7c6659fd](https://github.com/tldr-pages/tldr/commit/e26d7c6659fdd1a2ddd9dcf0d57c95eaa4615f94)

