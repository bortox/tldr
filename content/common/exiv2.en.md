---
author: ['jn64']
date: 1592770269
title: "exiv2, TLDR Pages"
description: "exiv2, Image metadata manipulation tool."
categories: "common"
---
> More information: <https://www.exiv2.org/manpage.html>.

- Print a summary of the image Exif metadata:

```bash
exiv2 path/to/file
```

- Print all metadata (Exif, IPTC, XMP) with interpreted values:

```bash
exiv2 -P kt path/to/file
```

- Print all metadata with raw values:

```bash
exiv2 -P kv path/to/file
```

- Delete all metadata from an image:

```bash
exiv2 -d a path/to/file
```

- Delete all metadata, preserving the file timestamp:

```bash
exiv2 -d a -k path/to/file
```

- Rename the file, prepending the date and time from metadata (not from the file timestamp):

```bash
exiv2 -r '%Y%m%d_%H%M%S_:basename:' path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[jn64](mailto:23169302+jn64@users.noreply.github.com) | exiv2: add page (#4093) | 2020-06-21T22:11:09 | [a6057cadb6b3](https://github.com/tldr-pages/tldr/commit/a6057cadb6b3a6aa23c0842de4f0c75c3c8cfb1d)

