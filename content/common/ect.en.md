---
author: ['bl-ue', 'Lynne', 'Marco Bonelli']
date: 1618083546
title: "ect"
description: "ect, Efficient Compression Tool."
categories: "common"
---
> File optimizer written in C++. It supports `.png`, `.jpg`, `.gzip` and `.zip` files.

> More information: <https://github.com/fhanau/Efficient-Compression-Tool>.

- Compress a file:

```bash
ect path/to/file.png
```

- Compress a file with specified compression level and multithreading (1=Fastest (Worst), 9=Slowest (Best), default is 3):

```bash
ect -9 --mt-deflate path/to/file.zip
```

- Compress all files in a directory recursively:

```bash
ect -recurse path/to/directory
```

- Compress a file, keeping the original modification time:

```bash
ect -keep path/to/file.png
```

- Compress a file, stripping metadata:

```bash
ect -strip path/to/file.png
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | ect: refresh (#5717) | 2021-04-10T21:39:06 | [2da2632f225f](https://github.com/tldr-pages/tldr/commit/2da2632f225f7dc9ac501fe9806ec78e714ee30c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Lynne](mailto:lynne@lynnesbian.space) | ect: add page (#2951) | 2019-04-28T13:17:03 | [b776bf1b6920](https://github.com/tldr-pages/tldr/commit/b776bf1b69204675fe13efbed0e54fa16678e00f)

