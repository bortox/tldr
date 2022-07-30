---
author: ['Dario Vladović', 'pxgamer', 'Guido Lena Cota', 'Felix Yan']
date: 1617292466
title: "numfmt"
description: "numfmt, Convert numbers to and from human-readable strings."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/numfmt>.

- Convert 1.5K (SI Units) to 1500:

```bash
numfmt --from=si 1.5K
```

- Convert 5th field (1-indexed) to IEC Units without converting header:

```bash
ls -l | numfmt --header=1 --field=5 --to=iec
```

- Convert to IEC units, pad with 5 characters, left aligned:

```bash
du -s * | numfmt --to=iec --format="%-5f"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[pxgamer](mailto:owzie123@gmail.com) | numfmt: add link to homepage | 2019-06-04T21:29:40 | [a69578d06ccb](https://github.com/tldr-pages/tldr/commit/a69578d06ccb2ff33b9eaa8ba4f26d539166ab7d)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

