---
author: ['Axel Navarro', 'Pierre Rudloff']
date: 1641649180
title: "reportbug"
description: "reportbug, Bug report tool of Debian distribution."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/reportbug/reportbug.html>.

- Generate a bug report about a specific package, then send it by e-mail:

```bash
reportbug package
```

- Report a bug that is not about a specific package (general problem, infrastructure, etc.):

```bash
reportbug other
```

- Write the bug report to a file instead of sending it by e-mail:

```bash
reportbug -o filename package
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[Pierre Rudloff](mailto:contact@rudloff.pro) | reportbug: add page (#4028) Co-authored-by: Andrik Albuquerque <andrik.albuquerque@gmail.com> | 2020-05-08T18:40:07 | [ac45c2b7a1b9](https://github.com/tldr-pages/tldr/commit/ac45c2b7a1b9f2264a3eea71b3d09b929387d2ea)

