---
author: ['Wilco']
date: 1604660353
title: "sublist3r"
description: "sublist3r, Fast subdomains enumeration tool for penetration testers."
categories: "common"
---
> More information: <https://github.com/aboul3la/Sublist3r>.

- Find subdomains for a domain:

```bash
sublist3r --domain domain_name
```

- Find subdomains for a domain, also enabling brute force search:

```bash
sublist3r --domain domain_name --bruteforce
```

- Save the found subdomains to a text file:

```bash
sublist3r --domain domain_name --output path/to/output_file
```

- Output all available options:

```bash
sublist3r --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Wilco](mailto:wilcovanbeijnum@gmail.com) | amass, httprobe, sublist3r, theHarvester: add page (#4912) | 2020-11-06T11:59:13 | [2f2a1144ffa3](https://github.com/tldr-pages/tldr/commit/2f2a1144ffa33fd43055c7cc7ef5c1b8d5ad224f)

