---
author: ['Vinfall']
date: 1632549880
title: "debsecan, TLDR Pages"
description: "debsecan, Debian Security Analyzer, a tool to list vulnerabilities on a particular Debian installation."
categories: "linux"
---
> More information: <https://gitlab.com/fweimer/debsecan>.

- List vulnerable installed packages on the current host:

```bash
debsecan
```

- List vulnerable installed packages of a specific suite:

```bash
debsecan --suite release_code_name
```

- List only fixed vulnerabilities:

```bash
debsecan --suite release_code_name --only-fixed
```

- List only fixed vulnerabilities of unstable ("sid") and mail to root:

```bash
debsecan --suite sid --only-fixed --format report --mailto root --update-history
```

- Upgrade vulnerable installed packages:

```bash
sudo apt upgrade $(debsecan --only-fixed --format packages)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Vinfall](mailto:91039000+Vinfall@users.noreply.github.com) | debsecan: add page (#6567) | 2021-09-25T08:04:40 | [dceaee6b1af5](https://github.com/tldr-pages/tldr/commit/dceaee6b1af5807ba9b70b9e7b11f581222ce49c)

