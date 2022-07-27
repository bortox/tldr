---
author: ['deeeeeeps', 'Lucas Gabriel Schneider', 'bl-ue', 'marchersimon']
date: 1618584134
title: "e2image, TLDR Pages"
description: "e2image, Save critical ext2/ext3/ext4 filesystem metadata to a file."
categories: "linux"
---
> More information: <https://manned.org/e2image>.

- Write metadata located on device to a specific file:

```bash
e2image /dev/sdXN path/to/image_file
```

- Print metadata located on device to stdout:

```bash
e2image /dev/sdXN -
```

- Restore the filesystem metadata back to the device:

```bash
e2image -I /dev/sdXN path/to/image_file
```

- Create a large raw sparse file with metadata at proper offsets:

```bash
e2image -r /dev/sdXN path/to/image_file
```

- Create a QCOW2 image file instead of a normal or raw image file:

```bash
e2image -Q /dev/sdXN path/to/image_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[deeeeeeps](mailto:73025353+deeeeeeps@users.noreply.github.com) | e2image: add page (#4795) | 2020-10-28T18:48:42 | [859988c83f3a](https://github.com/tldr-pages/tldr/commit/859988c83f3a2e29570ddd810c52a1e9edd36467)

