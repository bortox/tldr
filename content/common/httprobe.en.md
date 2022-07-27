---
author: ['Wilco']
date: 1604660353
title: "httprobe, TLDR Pages"
description: "httprobe, Take a list of domains and probe for working HTTP and HTTPS servers."
categories: "common"
---
> More information: <https://github.com/tomnomnom/httprobe>.

- Probe a list of domains from a text file:

```bash
cat input_file | httprobe
```

- Only check for HTTP if HTTPS is not working:

```bash
cat input_file | httprobe --prefer-https
```

- Probe additional ports with a given protocol:

```bash
cat input_file | httprobe -p https:2222
```

- Output all available options:

```bash
httprobe --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Wilco](mailto:wilcovanbeijnum@gmail.com) | amass, httprobe, sublist3r, theHarvester: add page (#4912) | 2020-11-06T11:59:13 | [2f2a1144ffa3](https://github.com/tldr-pages/tldr/commit/2f2a1144ffa33fd43055c7cc7ef5c1b8d5ad224f)

