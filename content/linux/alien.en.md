---
author: ['clanec15', 'Jonta']
date: 1635219285
title: "alien, TLDR Pages"
description: "alien, Convert different installation packages to other formats."
categories: "linux"
---
> More information: <https://manned.org/alien>.

- Convert a specific installation file to Debian format (`.deb` extension):

```bash
sudo alien --to-deb path/to/file
```

- Convert a specific installation file to Red Hat format (`.rpm` extension):

```bash
sudo alien --to-rpm path/to/file
```

- Convert a specific installation file to a Slackware installation file (`.tgz` extension):

```bash
sudo alien --to-tgz path/to/file
```

- Convert a specific installation file to Debian format and install on the system:

```bash
sudo alien --to-deb --install path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jonta](mailto:359397+Jonta@users.noreply.github.com) | alien: fix typo in command description (#7110) | 2021-10-26T05:34:45 | [4bae21a35b1c](https://github.com/tldr-pages/tldr/commit/4bae21a35b1cdf5957e16b9f9d5692feff630233)
[clanec15](mailto:forter125@outlook.com) | alien: add page (#7080) | 2021-10-19T22:41:02 | [dd9e99ed8fa2](https://github.com/tldr-pages/tldr/commit/dd9e99ed8fa2d6cc0b6e3a89d475d7b735129702)

