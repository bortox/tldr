---
author: ['Michael Pearce', 'Emily Grace Seville']
date: 1647882468
title: "repquota"
description: "repquota, Display a summary of existing file quotas for a filesystem."
categories: "linux"
---
> More information: <https://manned.org/repquota>.

- Report stats for all quotas in use:

```bash
sudo repquota -all
```

- Report quota stats for all users, even those who aren't using any of their quota:

```bash
sudo repquota -v filesystem
```

- Report on quotas for users only:

```bash
repquota --user filesystem
```

- Report on quotas for groups only:

```bash
sudo repquota --group filesystem
```

- Report on used quota and limits in a human-readable format:

```bash
sudo repquota --human-readable filesystem
```

- Report on all quotas for users and groups in a human-readable format:

```bash
sudo repquota -augs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Michael Pearce](mailto:pogomaniac@hotmail.com) | Update repquota.md (#1108) Later versions of repquota do not allow to view quota for individual users - use the quota command for [...] | 2016-10-24T09:38:52 | [a0633df4cf5c](https://github.com/tldr-pages/tldr/commit/a0633df4cf5cf3982220e968cb12772e50bce1c0)
[Michael Pearce](mailto:pogomaniac@hotmail.com) | repquota: add page (#983) | 2016-10-03T16:53:51 | [35b685ff9c67](https://github.com/tldr-pages/tldr/commit/35b685ff9c67ff75bd70da331f68249ecd45785f)

