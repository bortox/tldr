---
author: ['George Vlahavas', 'Seth Falco']
date: 1629050349
title: "slapt-src"
description: "slapt-src, A utility to automate building of slackbuilds."
categories: "linux"
---
> SlackBuild sources need to be configured in the slapt-srcrc file.

> More information: <https://github.com/jaos/slapt-src>.

- Update the list of available slackbuilds and versions:

```bash
slapt-src --update
```

- List all available slackbuilds:

```bash
slapt-src --list
```

- Fetch, build and install the specified slackbuild(s):

```bash
slapt-src --install slackbuild_name
```

- Locate slackbuilds by their name or description:

```bash
slapt-src --search search_term
```

- Display information about a slackbuild:

```bash
slapt-src --show slackbuild_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[George Vlahavas](mailto:vlahavas@gmail.com) | slapt-src, spi: add page, slapt-get: fix example (#5014) | 2020-12-14T13:05:58 | [cb83e50f5522](https://github.com/tldr-pages/tldr/commit/cb83e50f5522477e0f561f0e7e9137ed651549e9)

