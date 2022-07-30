---
author: ['João C Fukuda']
date: 1634182391
title: "searchsploit"
description: "searchsploit, Searchsploit searches exploit database's database for exploits, shellcodes and/or papers."
categories: "common"
---
> If known version numbers are used as search terms, exploits for both the exact version and others whose version range covers the one specified are shown.

> More information: <https://www.exploit-db.com/searchsploit>.

- Search for an exploit, shellcode, or paper:

```bash
searchsploit search_terms
```

- Search for a known specific version, e.g. sudo version 1.8.27:

```bash
searchsploit sudo 1.8.27
```

- Show the exploit-db link to the found resources:

```bash
searchsploit --www search_terms
```

- Make a copy of the resource to the current directory (requires the number of the exploit):

```bash
searchsploit --mirror exploit_number
```

- Open the resource to read with the pager defined in the `$PAGER` environment variable:

```bash
searchsploit --explore exploit_number
```

- Update the local exploit database:

```bash
searchsploit --update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[João C Fukuda](mailto:37672942+JoaoFukuda@users.noreply.github.com) | searchsploit: add page (#6826) | 2021-10-14T05:33:11 | [992898b2a575](https://github.com/tldr-pages/tldr/commit/992898b2a5752270f010f3b7347491aec6e17dd1)

