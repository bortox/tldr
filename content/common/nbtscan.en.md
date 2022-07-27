---
author: ['bl-ue', 'Starbeamrainbowlabs']
date: 1621541621
title: "nbtscan, TLDR Pages"
description: "nbtscan, Scan networks for NetBIOS name information."
categories: "common"
---
> More information: <https://github.com/resurrecting-open-source-projects/nbtscan>.

- Scan a network for NetBIOS names:

```bash
nbtscan 192.168.0.1/24
```

- Scan a single IP address:

```bash
nbtscan 192.168.0.1
```

- Display verbose output:

```bash
nbtscan -v 192.168.0.1/24
```

- Display output in `/etc/hosts` format:

```bash
nbtscan -e 192.168.0.1/24
```

- Read IP addresses / networks to scan from a file:

```bash
nbtscan -f path/to/file.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | nbtscan: add page (#5434) | 2021-03-14T06:20:34 | [8c38dc1dd749](https://github.com/tldr-pages/tldr/commit/8c38dc1dd749e5cd200304257620aa7586a730b2)

