---
author: ['Kirill Stryaponov']
date: 1643706301
title: "cwebp, TLDR Pages"
description: "cwebp, Compress an image file to a WebP file."
categories: "common"
---
> More information: <https://developers.google.com/speed/webp/docs/cwebp>.

- Compress a WebP file with default settings (q = 75) to the [o]utput file:

```bash
cwebp path/to/image_file -o path/to/output.webp
```

- Compress a WebP file with the best [q]uality and largest file size:

```bash
cwebp path/to/image_file -o path/to/output.webp -q 100
```

- Compress a WebP file with the worst [q]uality and smallest file size:

```bash
cwebp path/to/image_file -o path/to/output.webp -q 0
```

- Compress a WebP file and apply resize to image:

```bash
cwebp path/to/image_file -o path/to/output.webp -resize width height
```

- Compress a WebP file and drop alpha channel information:

```bash
cwebp path/to/image_file -o path/to/output.webp -noalpha
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kirill Stryaponov](mailto:stryaponoff@gmail.com) | cwebp: add page (#7722) * cwebp: add page * cwebp: add russian translation * cwebp: update descriptions * cwebp: update Russian [...] | 2022-02-01T10:05:01 | [3e8b075813d2](https://github.com/tldr-pages/tldr/commit/3e8b075813d2ba46324422e6e3b2f133706293b1)

