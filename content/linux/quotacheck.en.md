---
author: ['Waldir Pimenta', 'Michael Pearce', 'Emily Grace Seville']
date: 1647882468
title: "quotacheck, TLDR Pages"
description: "quotacheck, Scan a filesystem for disk usage; create, check and repair quota files."
categories: "linux"
---
> It is best to run quota check with quotas turned off to prevent damage or loss to quota files.

> More information: <https://manned.org/quotacheck>.

- Check quotas on all mounted non-NFS filesystems:

```bash
sudo quotacheck --all
```

- Force check even if quotas are enabled (this can cause damage or loss to quota files):

```bash
sudo quotacheck --force mountpoint
```

- Check quotas on a given filesystem in debug mode:

```bash
sudo quotacheck --debug mountpoint
```

- Check quotas on a given filesystem, displaying the progress:

```bash
sudo quotacheck --verbose mountpoint
```

- Check user quotas:

```bash
sudo quotacheck --user user mountpoint
```

- Check group quotas:

```bash
sudo quotacheck --group group mountpoint
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | quotacheck: minor tweaks (#1119) | 2016-10-16T17:43:32 | [c032e9795461](https://github.com/tldr-pages/tldr/commit/c032e97954613b797ecb39f421f5311de22b3278)
[Michael Pearce](mailto:pogomaniac@hotmail.com) | quotacheck: add page (#1002) | 2016-10-16T15:51:30 | [c5bd622d7b73](https://github.com/tldr-pages/tldr/commit/c5bd622d7b73b3d234250ce2d5054b69e945eeff)

