---
author: ['kalebo', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629110041
title: "logwatch"
description: "logwatch, Summarizes many different logs for common services (e.g. apache, pam_unix, sshd, etc.) in a single report."
categories: "linux"
---
> More information: <https://manned.org/logwatch>.

- Analyze logs for a range of dates at a certain level of detail:

```bash
logwatch --range yesterday|today|all|help --detail low|medium|others'
```

- Restrict report to only include information for a selected service:

```bash
logwatch --range all --service apache|pam_unix|etc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[kalebo](mailto:kaleb.olson@gmail.com) | logwatch: add page (#1311) Logwatch is a useful command to summarize log files. It can be configured to use settings from it's config [...] | 2017-05-24T10:43:38 | [4e544c1230bd](https://github.com/tldr-pages/tldr/commit/4e544c1230bda44cfe6125e25051a611d22319ef)

