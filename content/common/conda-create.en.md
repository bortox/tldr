---
author: ['Seth Falco', 'Luke Harold Miles']
date: 1629050349
title: "conda create, TLDR Pages"
description: "conda create, Create new conda environments."
categories: "common"
---
> More information: <https://docs.conda.io/projects/conda/en/latest/commands/create.html>.

- Create a new environment named `py39`, and install Python 3.9 and NumPy v1.11 or above in it:

```bash
conda create --yes --name py39 python=3.9 "numpy>=1.11"
```

- Make exact copy of an environment:

```bash
conda create --clone py39 --name py39-copy
```

- Create a new environment with a specified name and install a given package:

```bash
conda create --name env_name package_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Luke Harold Miles](mailto:luke@mm.st) | conda-create: add page (#6043) | 2021-05-27T03:14:24 | [0ddefb9a9f18](https://github.com/tldr-pages/tldr/commit/0ddefb9a9f18996cb02a2ec05452ddd7f7b0d3c4)

