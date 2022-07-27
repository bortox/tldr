---
author: ['Waldir Pimenta', 'Florian', 'Owen Voke', 'Marco Bonelli', 'dcaspi', 'Yann Collet', 'Lucas Gabriel Schneider']
date: 1612112718
title: "zstd, TLDR Pages"
description: "zstd, Compress or decompress files with Zstandard compression."
categories: "common"
---
> More information: <https://github.com/facebook/zstd>.

- Compress a file into a new file with the `.zst` suffix:

```bash
zstd file
```

- Decompress a file:

```bash
zstd -d file.zst
```

- Decompress to stdout:

```bash
zstd -dc file.zst
```

- Compress a file specifying the compression level, where 1=fastest, 19=slowest and 3=default:

```bash
zstd -level file
```

- Unlock higher compression levels (up to 22) using more memory (both for compression and decompression):

```bash
zstd --ultra -level file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Yann Collet](mailto:Cyan4973@users.noreply.github.com) | zstd: update compression level sentences (#4121) | 2020-06-24T00:25:45 | [c3699ce5463c](https://github.com/tldr-pages/tldr/commit/c3699ce5463c2beb495ea732e0d2b1c99360c9b2)
[Florian](mailto:KopfKrieg@users.noreply.github.com) | zstd: reworded a sentence (as discussed in PR #3791) (#3814) | 2020-01-30T01:41:22 | [9abba96cc056](https://github.com/tldr-pages/tldr/commit/9abba96cc056699e6426603b9c7420a365eb1e97)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[dcaspi](mailto:dcaspi@users.noreply.github.com) | zstd: add page (#2646) | 2018-12-18T16:43:09 | [1620d8fb8e45](https://github.com/tldr-pages/tldr/commit/1620d8fb8e45162164ad38afad554ba6e5801160)

