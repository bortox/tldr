---
author: ['Seth Falco', 'Sosthene-Guedon']
date: 1629050349
title: "brotli, TLDR Pages"
description: "brotli, Compress/uncompress files with Brotli compression."
categories: "common"
---
> More information: <https://github.com/google/brotli>.

- Compress a file, creating a compressed version next to the file:

```bash
brotli file.ext
```

- Decompress a file, creating an uncompressed version next to the file:

```bash
brotli -d file.ext.br
```

- Compress a file specifying the output filename:

```bash
brotli file.ext -o compressed_file.ext.br
```

- Decompress a Brotli file specifying the output filename:

```bash
brotli -d compressed_file.ext.br -o file.ext
```

- Specify the compression level. 1=Fastest (Worst), 11=Slowest (Best):

```bash
brotli -q 11 file.ext -o compressed_file.ext.br
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Sosthene-Guedon](mailto:51865119+Sosthene-Guedon@users.noreply.github.com) | brotli: add page (#5016) | 2020-12-12T20:52:03 | [05cdce5001cf](https://github.com/tldr-pages/tldr/commit/05cdce5001cfce6c98903460fdfc99652fe1a212)

