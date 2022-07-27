---
author: ['Emily Grace Seville', 'jxu', 'Eridani', 'Arthur Bols', 'Seth Falco']
date: 1647882468
title: "snap, TLDR Pages"
description: "snap, Tool for managing the 'snap' self-contained software packages."
categories: "linux"
---
> Similar to what `apt` is for ".deb".

> More information: <https://manned.org/snap>.

- Search for a package:

```bash
snap find package_name
```

- Install a package:

```bash
snap install package_name
```

- Update a package:

```bash
snap refresh package_name
```

- Update a package to another channel (track, risk, or branch):

```bash
snap refresh package_name --channel=channel
```

- Update all packages:

```bash
snap refresh
```

- Display basic information about installed snap software:

```bash
snap list
```

- Uninstall a package:

```bash
snap remove package_name
```

- Check for recent snap changes in the system:

```bash
snap changes
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Seth Falco](mailto:seth@falco.fun) | snap: add example to update to another channel (#6046) | 2021-05-28T00:44:39 | [c0ea286edec0](https://github.com/tldr-pages/tldr/commit/c0ea286edec036e38ce69ac75624dcefc0d76069)
[jxu](mailto:7989982+jxu@users.noreply.github.com) | snap: add update package (#3872) | 2020-02-26T04:17:21 | [7b364ecea9e2](https://github.com/tldr-pages/tldr/commit/7b364ecea9e2600594f39afd33fe370263a7eba2)
[Arthur Bols](mailto:arthur.bolsbe@gmail.com) | snap: add refresh example (#2475) | 2018-10-22T00:07:28 | [ada2c2f36474](https://github.com/tldr-pages/tldr/commit/ada2c2f3647404a015bdcdaeca7afd48a11b638c)
[Eridani](mailto:eridanired@users.noreply.github.com) | snap: add page (#1749) | 2017-12-08T04:58:59 | [087a8a655758](https://github.com/tldr-pages/tldr/commit/087a8a655758cf9520bd73c9bc23d91ebabe8d38)

