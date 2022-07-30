---
author: ['bl-ue', 'Seth Falco']
date: 1629050349
title: "theHarvester"
description: "theHarvester, A tool designed to be used in the early stages of a penetration test."
categories: "common"
---
> More information: <https://github.com/laramies/theHarvester>.

- Gather information on a domain using Google:

```bash
theHarvester --domain domain_name --source google
```

- Gather information on a domain using multiple sources:

```bash
theHarvester --domain domain_name --source google,bing,crtsh
```

- Change the limit of results to work with:

```bash
theHarvester --domain domain_name --source google --limit 200
```

- Save the output to two files in XML and HTML format:

```bash
theHarvester --domain domain_name --source google --file output_file_name
```

- Output all available options:

```bash
theHarvester --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | theHarvester: rename to theharvester (#5380) | 2021-03-08T11:38:07 | [56c45a0e76c5](https://github.com/tldr-pages/tldr/commit/56c45a0e76c5588ba1f8b3ee0a5432360732daf9)

