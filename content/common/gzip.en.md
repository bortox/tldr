---
author: ['Donovan Allen', 'Agniva De Sarker', 'marcan2020', 'rprieto', 'lord63', 'Tony Marjakangas', 'Ruben Vereecken', 'scrouthtv', 'marchersimon']
date: 1625432553
title: "gzip"
description: "gzip, Compress/uncompress files with gzip compression (LZ77)."
categories: "common"
---
> More information: <https://www.gnu.org/software/gzip/manual/gzip.html>.

- Compress a file, replacing it with a gzipped compressed version:

```bash
gzip file.ext
```

- Decompress a file, replacing it with the original uncompressed version:

```bash
gzip -d file.ext.gz
```

- Compress a file, keeping the original file:

```bash
gzip --keep file.ext
```

- Compress a file specifying the output filename:

```bash
gzip -c file.ext > compressed_file.ext.gz
```

- Decompress a gzipped file specifying the output filename:

```bash
gzip -c -d file.ext.gz > uncompressed_file.ext
```

- Specify the compression level. 1=Fastest (Worst), 9=Slowest (Best), Default level is 6:

```bash
gzip -9 -c file.ext > compressed_file.ext.gz
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[scrouthtv](mailto:lennivh24@gmail.com) | gzip: add --keep example (#6193) | 2021-07-04T23:02:33 | [00e43965213e](https://github.com/tldr-pages/tldr/commit/00e43965213e6f3a675040abb9f62bff5507ec83)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[marcan2020](mailto:marcan2020@gmail.com) | gzip: correct example description. | 2019-02-06T12:52:56 | [15cf138e474f](https://github.com/tldr-pages/tldr/commit/15cf138e474f5a940d9bc0f9e661bd51fec71429)
[Donovan Allen](mailto:me@donovanallen.net) | gzip: Remove gz extension from output file (#2015) | 2018-03-11T15:39:17 | [930cfe7f8925](https://github.com/tldr-pages/tldr/commit/930cfe7f89259df5df3aadcad21cb9ed4c74b033)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Tony Marjakangas](mailto:Marza@users.noreply.github.com) | Fixed typo in gzip.md | 2015-12-29T21:31:19 | [125768b56ae0](https://github.com/tldr-pages/tldr/commit/125768b56ae016f099efa152930060789f077bdf)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

