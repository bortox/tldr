---
author: ['Starbeamrainbowlabs']
date: 1612312069
title: "rankmirrors"
description: "rankmirrors, Rank a list of Pacman mirrors by connection and opening speed."
categories: "linux"
---
> Writes the new mirrorlist to stdout.

> More information: <https://wiki.archlinux.org/index.php/mirrors>.

- Rank a mirror list:

```bash
rankmirrors /etc/pacman.d/mirrorlist
```

- Output only a given number of the top ranking servers:

```bash
rankmirrors -n number /etc/pacman.d/mirrorlist
```

- Be verbose when generating the mirrorlist:

```bash
rankmirrors -v /etc/pacman.d/mirrorlist
```

- Test only a specific URL:

```bash
rankmirrors --url url
```

- Output only the response times instead of a full mirrorlist:

```bash
rankmirrors --times /etc/pacman.d/mirrorlist
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | rankmirrors: add page (#5217) | 2021-02-03T01:27:49 | [9920c058caaa](https://github.com/tldr-pages/tldr/commit/9920c058caaa5f9a789eba3c27d24099260ea3c2)

