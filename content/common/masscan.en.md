---
author: ['ciph3rz', 'Elkana Bardugo', 'CleanMachine1']
date: 1656619054
title: "Masscan"
description: "Masscan, Network scanner for scanning as fast as possible."
categories: "common"
---
> Best run with elevated privileges. Nmap compatibility run `masscan --nmap` to find out more.

> More information: <https://github.com/robertdavidgraham/masscan>.

- Scan an IP or network subnet for port 80:

```bash
masscan ip_address|network_prefix --ports 80
```

- Scan a class B subnet for the top 100 ports at 100,000 packets per second:

```bash
masscan 10.0.0.0/16 --top-ports 100 --rate 100000
```

- Scan a class B subnet avoiding ranges from a specific exclude file:

```bash
masscan 10.0.0.0/16 --top-ports 100 --excludefile path/to/file
```

- Scan the Internet for port 443:

```bash
masscan 0.0.0.0/0 --ports 443 --rate 10000000
```

- Scan the Internet for a specific port range and export to a file:

```bash
masscan 0.0.0.0/0 --ports 0-65535 -output-format binary|grepable|json|list|xml --output-filename path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | Fix spelling mistakes | 2022-06-30T21:57:34 | [a0828299099a](https://github.com/tldr-pages/tldr/commit/a0828299099a2224eca625dcf412c341124c5011)
[Elkana Bardugo](mailto:ttv200@gmail.com) | masscan: correct typo in hypen (#7446) | 2021-11-17T18:53:43 | [0aa0fe55cd3e](https://github.com/tldr-pages/tldr/commit/0aa0fe55cd3ee1b713814b9791f05b0f58f70609)
[ciph3rz](mailto:46655414+ciph3rz@users.noreply.github.com) | masscan: add page (#6986) | 2021-10-17T16:36:55 | [7c85dd0c7e9c](https://github.com/tldr-pages/tldr/commit/7c85dd0c7e9cd1ba8407d957e22c42d67d9e14b1)

