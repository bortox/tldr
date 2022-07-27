---
author: ['Juri']
date: 1634429541
title: "dirb, TLDR Pages"
description: "dirb, Scan HTTP-based webservers for directories and files."
categories: "linux"
---
> More information: <http://dirb.sourceforge.net>.

- Scan a webserver using the default wordlist:

```bash
dirb https://example.org
```

- Scan a webserver using a custom wordlist:

```bash
dirb https://example.org path/to/wordlist.txt
```

- Scan a webserver non-recursively:

```bash
dirb https://example.org -r
```

- Scan a webserver using a specified user-agent and cookie for HTTP-requests:

```bash
dirb https://example.org -a user_agent_string -c cookie_string
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | dirb: add page (#6960) | 2021-10-17T02:12:21 | [bcf9a4ad8e69](https://github.com/tldr-pages/tldr/commit/bcf9a4ad8e6928806b3892ca78aeecedaa770d28)

