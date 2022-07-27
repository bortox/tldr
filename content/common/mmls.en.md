---
author: ['z7y8hsBP']
date: 1580379022
title: "mmls, TLDR Pages"
description: "mmls, Display the partition layout of a volume system."
categories: "common"
---
> More information: <https://wiki.sleuthkit.org/index.php?title=Mmls>.

- Display the partition table stored in an image file:

```bash
mmls path/to/image_file
```

- Display the partition table with an additional column for the partition size:

```bash
mmls -B -i path/to/image_file
```

- Display the partition table in a split EWF image:

```bash
mmls -i ewf image.e01 image.e02
```

- Display nested partition tables:

```bash
mmls -t nested_table_type -o offset path/to/image_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[z7y8hsBP](mailto:51470766+z7y8hsBP@users.noreply.github.com) | mmls: add page (#3812) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> Co-authored-by: Zlatan Vasović [...] | 2020-01-30T11:10:22 | [2769e54b4159](https://github.com/tldr-pages/tldr/commit/2769e54b4159d3c5c679fa9d63be1ce234cb61c0)

