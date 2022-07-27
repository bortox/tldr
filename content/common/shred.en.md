---
author: ['Dario Vladović', 'Hayden Schiff', 'marchersimon']
date: 1617292466
title: "shred, TLDR Pages"
description: "shred, Overwrite files to securely delete data."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/shred>.

- Overwrite a file:

```bash
shred file
```

- Overwrite a file, leaving zeroes instead of random data:

```bash
shred --zero file
```

- Overwrite a file 25 times:

```bash
shred -n25 file
```

- Overwrite a file and remove it:

```bash
shred --remove file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | shred: add link (#5567) | 2021-03-30T09:32:11 | [7c1994af0ba7](https://github.com/tldr-pages/tldr/commit/7c1994af0ba7d09bdb76f4fe0909862d85b09e56)
[Hayden Schiff](mailto:oxguy3@gmail.com) | shred: typo fix | 2016-02-05T18:03:46 | [6f8ec67bcb8c](https://github.com/tldr-pages/tldr/commit/6f8ec67bcb8c8069b5731541d8c5a89d2277adfe)
[Hayden Schiff](mailto:oxguy3@gmail.com) | shred: add page | 2016-02-05T17:22:47 | [1efe814fc7b1](https://github.com/tldr-pages/tldr/commit/1efe814fc7b14b43eaeeff2f9e9b2714f9379c80)

