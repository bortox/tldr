---
author: ['Austin', 'Seth Falco']
date: 1656325392
title: "dfc, TLDR Pages"
description: "dfc, Gives an overview of the filesystem disk space usage with colors and graphs."
categories: "common"
---
> More information: <https://projects.gw-computing.net/projects/dfc/wiki>.

- Display filesystems and their disk usage in human-readable form with colors and graphs:

```bash
dfc
```

- Display all filesystems including pseudo, duplicate and inaccessible filesystems:

```bash
dfc -a
```

- Display filesystems without color:

```bash
dfc -c never
```

- Display filesystems containing "ext" in the filesystem type:

```bash
dfc -t ext
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Austin](mailto:Hoi15A@users.noreply.github.com) | cryfs, df, dfc, fls, ipfs, duperemove, edquote, lsattr, diskutil: (#4427) consistently use "filesystem" | 2020-10-03T16:38:06 | [cfe462c57f20](https://github.com/tldr-pages/tldr/commit/cfe462c57f20c344dad34717378c442dc32cadc2)
[Austin](mailto:Hoi15A@users.noreply.github.com) | dfc: make "file system" one word | 2020-10-02T21:23:24 | [288e2afcb2ee](https://github.com/tldr-pages/tldr/commit/288e2afcb2eee3e5769651ff5576f213c2b1088b)
[Austin](mailto:Hoi15A@users.noreply.github.com) | dfc: link to wiki instead of mentioning df Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2020-10-02T21:23:24 | [410d95598803](https://github.com/tldr-pages/tldr/commit/410d955988039f4af7a55c581f633556553d99ef)
[Austin](mailto:Hoi15A@users.noreply.github.com) | dfc: add page | 2020-10-02T21:23:24 | [370637c87b17](https://github.com/tldr-pages/tldr/commit/370637c87b1765ddfec6dd871d36406562b5f335)

