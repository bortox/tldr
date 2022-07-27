---
author: ['Marco Bonelli', 'Agniva De Sarker', 'Hayden Schiff', 'bl-ue', 'Starbeamrainbowlabs']
date: 1619892654
title: "7zr, TLDR Pages"
description: "7zr, File archiver with a high compression ratio."
categories: "common"
---
> Similar to `7z` except that it only supports `.7z` files.

> More information: <https://www.7-zip.org>.

- [a]rchive a file or directory:

```bash
7zr a path/to/archive.7z path/to/file_or_directory
```

- Encrypt an existing archive (including file names):

```bash
7zr a path/to/encrypted.7z -ppassword -mhe=on path/to/archive.7z
```

- E[x]tract an archive preserving the original directory structure:

```bash
7zr x path/to/archive.7z
```

- E[x]tract an archive to a specific directory:

```bash
7zr x path/to/archive.7z -opath/to/output
```

- E[x]tract an archive to stdout:

```bash
7zr x path/to/archive.7z -so
```

- [l]ist the contents of an archive:

```bash
7zr l path/to/archive.7z
```

- List available archive types:

```bash
7zr i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | 7z, 7za, 7zr: updates (#5432) * 7z, 7za, 7zr: updates * Apply suggestions from code review Co-authored-by: marchersimon [...] | 2021-05-01T20:10:54 | [d6f6b88a7fa3](https://github.com/tldr-pages/tldr/commit/d6f6b88a7fa30969f4fb8ac44d5197330b82de31)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: add missing `or_directory` where needed. This commit adds the missing `_or_directory` to any example which is specifying an [...] | 2019-02-08T20:43:24 | [f79f6011e0f2](https://github.com/tldr-pages/tldr/commit/f79f6011e0f298311848b5f38d66c309d4b92665)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | 7z*.md: Modify tokens (#1009) | 2016-08-18T11:50:36 | [e42a45fba937](https://github.com/tldr-pages/tldr/commit/e42a45fba937fa2fcc07e48b9d7f630c404cdaed)
[Hayden Schiff](mailto:haydenschiff@gmail.com) | 7za/7zr: fixed incorrect command names | 2016-02-23T01:52:36 | [64fa60df1606](https://github.com/tldr-pages/tldr/commit/64fa60df1606e3a6ca0e27670862f36aaf6a6517)
[Hayden Schiff](mailto:haydenschiff@gmail.com) | 7z/7za/7zr: clearer descriptions, replaced multipart example with list example | 2016-02-23T01:51:52 | [3caf18e47e00](https://github.com/tldr-pages/tldr/commit/3caf18e47e0081cdfb99e3bfe54446b0c15b11cd)
[Hayden Schiff](mailto:oxguy3@gmail.com) | 7zr: add page (based on 7za) | 2016-02-22T22:50:45 | [8257a02c65cb](https://github.com/tldr-pages/tldr/commit/8257a02c65cb79e5e26a8bebdb312af6a7c2ec4b)

