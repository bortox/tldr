---
author: ['Patrice Denis', 'Pierre Rudloff']
date: 1617209183
title: "a2dissite"
description: "a2dissite, Disable an Apache virtual host on Debian-based OSes."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/apache2/a2dissite.8.en.html>.

- Disable a virtual host:

```bash
sudo a2dissite virtual_host
```

- Don't show informative messages:

```bash
sudo a2dissite --quiet virtual_host
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | a2dissite: update en link to latest instead of buster | 2021-03-31T18:46:23 | [66d2f6853ddc](https://github.com/tldr-pages/tldr/commit/66d2f6853ddcc80d86a4867d496b38fb250a4f08)
[Pierre Rudloff](mailto:contact@rudloff.pro) | a2disconf, a2dismod, a2dissite, a2enconf, a2enmod, a2ensite, a2query: add page (#3609) | 2019-11-28T22:20:50 | [f9ef67608e3d](https://github.com/tldr-pages/tldr/commit/f9ef67608e3d1f35d9383dc792e1ec6f5df02275)

