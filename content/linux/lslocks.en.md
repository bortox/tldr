---
author: ['Waldir Pimenta', 'RH-sdavey', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629110041
title: "lslocks, TLDR Pages"
description: "lslocks, List local system locks."
categories: "linux"
---
> More information: <https://manned.org/lslocks>.

- List all local system locks:

```bash
lslocks
```

- List locks with defined column headers:

```bash
lslocks --output PID,COMMAND,PATH
```

- List locks producing a raw output (no columns), and without column headers:

```bash
lslocks --raw --noheadings
```

- List locks by PID input:

```bash
lslocks --pid PID
```

- List locks with JSON output to stdout:

```bash
lslocks --json
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[RH-sdavey](mailto:32485509+RH-sdavey@users.noreply.github.com) | lslocks: add page (#3037) | 2019-05-28T11:27:22 | [f25dd60c15fa](https://github.com/tldr-pages/tldr/commit/f25dd60c15faf7b640ee1ee5c95f1777ffa1d6fc)

