---
author: ['Axel Navarro', 'Pierre Rudloff']
date: 1641649180
title: "a2query"
description: "a2query, Retrieve runtime configuration from Apache on Debian-based OSes."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/apache2/a2query.html>.

- List enabled Apache modules:

```bash
sudo a2query -m
```

- Check if a specific module is installed:

```bash
sudo a2query -m module_name
```

- List enabled virtual hosts:

```bash
sudo a2query -s
```

- Display the currently enabled Multi Processing Module:

```bash
sudo a2query -M
```

- Display the Apache version:

```bash
sudo a2query -v
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[Pierre Rudloff](mailto:contact@rudloff.pro) | a2disconf, a2dismod, a2dissite, a2enconf, a2enmod, a2ensite, a2query: add page (#3609) | 2019-11-28T22:20:50 | [f9ef67608e3d](https://github.com/tldr-pages/tldr/commit/f9ef67608e3d1f35d9383dc792e1ec6f5df02275)

