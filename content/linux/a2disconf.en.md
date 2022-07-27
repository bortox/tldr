---
author: ['Pierre Rudloff', 'Patrice Denis']
date: 1617209183
title: "a2disconf, TLDR Pages"
description: "a2disconf, Disable an Apache configuration file on Debian-based OSes."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/apache2/a2disconf.8.en.html>.

- Disable a configuration file:

```bash
sudo a2disconf configuration_file
```

- Don't show informative messages:

```bash
sudo a2disconf --quiet configuration_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | a2disconf: update en link to latest instead of buster | 2021-03-31T18:46:23 | [95467a3beca7](https://github.com/tldr-pages/tldr/commit/95467a3beca782fd26c938e9ccc011d5ce3f8a9e)
[Pierre Rudloff](mailto:contact@rudloff.pro) | a2disconf, a2dismod, a2dissite, a2enconf, a2enmod, a2ensite, a2query: add page (#3609) | 2019-11-28T22:20:50 | [f9ef67608e3d](https://github.com/tldr-pages/tldr/commit/f9ef67608e3d1f35d9383dc792e1ec6f5df02275)

