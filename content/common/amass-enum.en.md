---
author: ['Wilco']
date: 1604660353
title: "amass enum, TLDR Pages"
description: "amass enum, Find subdomains of a domain."
categories: "common"
---
> More information: <https://github.com/OWASP/Amass/blob/master/doc/user_guide.md#the-enum-subcommand>.

- Passively find subdomains of a domain:

```bash
amass enum -passive -d domain_name
```

- Find subdomains of a domain and actively verify them attempting to resolve the found subdomains:

```bash
amass enum -active -d domain_name -p 80,443,8080
```

- Do a brute force search for subdomains:

```bash
amass enum -brute -d domain_name
```

- Save the results to a text file:

```bash
amass enum -o output_file -d domain_name
```

- Save the results to a database:

```bash
amass enum -o output_file -dir path/to/database_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Wilco](mailto:wilcovanbeijnum@gmail.com) | amass, httprobe, sublist3r, theHarvester: add page (#4912) | 2020-11-06T11:59:13 | [2f2a1144ffa3](https://github.com/tldr-pages/tldr/commit/2f2a1144ffa33fd43055c7cc7ef5c1b8d5ad224f)

