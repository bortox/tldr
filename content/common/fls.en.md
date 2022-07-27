---
author: ['Austin', 'Seth Falco', 'z7y8hsBP']
date: 1656325392
title: "fls, TLDR Pages"
description: "fls, List files and directories in an image file or device."
categories: "common"
---
> More information: <https://wiki.sleuthkit.org/index.php?title=Fls>.

- Build a recursive fls list over a device, output paths will start with C:

```bash
fls -r -m C: /dev/loop1p1
```

- Analyze a single partition, providing the sector offset at which the filesystem starts in the image:

```bash
fls -r -m C: -o sector path/to/image_file
```

- Analyze a single partition, providing the timezone of the original system:

```bash
fls -r -m C: -z timezone /dev/loop1p1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Austin](mailto:Hoi15A@users.noreply.github.com) | cryfs, df, dfc, fls, ipfs, duperemove, edquote, lsattr, diskutil: (#4427) consistently use "filesystem" | 2020-10-03T16:38:06 | [cfe462c57f20](https://github.com/tldr-pages/tldr/commit/cfe462c57f20c344dad34717378c442dc32cadc2)
[z7y8hsBP](mailto:51470766+z7y8hsBP@users.noreply.github.com) | fls: add page (#3786) * fls: add page Added a (very) basic description of fls * Update fls.md Changed imagefile to device in the first [...] | 2020-02-03T20:07:11 | [0ac937674dee](https://github.com/tldr-pages/tldr/commit/0ac937674dee1f4281a00de9373fce093b864a7f)

