---
author: ['Lucas Gabriel Schneider', 'Luca Dorigo', 'sebastientinel']
date: 1612112718
title: "unshadow, TLDR Pages"
description: "unshadow, Utility provided by the John the Ripper project to obtain the traditional Unix password file if the system uses shadow passwords."
categories: "linux"
---
> More information: <https://www.openwall.com/john/>.

- Combine the `/etc/shadow` and `/etc/passwd` of the current system:

```bash
sudo unshadow /etc/passwd /etc/shadow
```

- Combine two arbitrary shadow and password files:

```bash
sudo unshadow path/to/passwd path/to/shadow
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[Luca Dorigo](mailto:dorigoluca@gmail.com) | unshadow: add page (#4041) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-05-14T00:43:50 | [178e6959abbc](https://github.com/tldr-pages/tldr/commit/178e6959abbc1f7f5d2f9b0c2b854a20c016d70f)

