---
author: ['Wilco']
date: 1604660353
title: "amass intel, TLDR Pages"
description: "amass intel, Collect open source intel on an organisation like root domains and ASNs."
categories: "common"
---
> More information: <https://github.com/OWASP/Amass/blob/master/doc/user_guide.md#the-intel-subcommand>.

- Find root domains in an IP address range:

```bash
amass intel -addr 192.168.0.1-254
```

- Use active recon methods:

```bash
amass intel -active -addr 192.168.0.1-254
```

- Find root domains related to a domain:

```bash
amass intel -whois -d domain_name
```

- Find ASNs belonging to an organisation:

```bash
amass intel -org organisation_name
```

- Find root domains belonging to a given Autonomous System Number:

```bash
amass intel -asn asn
```

- Save results to a text file:

```bash
amass intel -o output_file -whois -d domain_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Wilco](mailto:wilcovanbeijnum@gmail.com) | amass, httprobe, sublist3r, theHarvester: add page (#4912) | 2020-11-06T11:59:13 | [2f2a1144ffa3](https://github.com/tldr-pages/tldr/commit/2f2a1144ffa33fd43055c7cc7ef5c1b8d5ad224f)

