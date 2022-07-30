---
author: ['Lucas Gabriel Schneider', 'Sébastien Wains']
date: 1629110041
title: "mpstat"
description: "mpstat, Report CPU statistics."
categories: "linux"
---
> More information: <https://manned.org/mpstat>.

- Display CPU statistics every 2 seconds:

```bash
mpstat 2
```

- Display 5 reports, one by one, at 2 second intervals:

```bash
mpstat 2 5
```

- Display 5 reports, one by one, from a given processor, at 2 second intervals:

```bash
mpstat -P 0 2 5
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Sébastien Wains](mailto:sebw@users.noreply.github.com) | mpstat: add page (#1301) * mpstat: add page * Update mpstat - Incrementally added options - Simplified the descriptions - Tokenified [...] | 2017-03-17T14:52:06 | [da09e78bc747](https://github.com/tldr-pages/tldr/commit/da09e78bc747a63f78818eea6a4519c9f51ba52b)

