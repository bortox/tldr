---
author: ['Janek', 'Daniel Cervenkov']
date: 1623095042
title: "pdfjoin, TLDR Pages"
description: "pdfjoin, PDF merging utility based on pdfjam."
categories: "common"
---
> More information: <https://github.com/rrthomas/pdfjam-extras>.

- Merge two PDFs into one with the default suffix "joined":

```bash
pdfjoin path/to/file1.pdf path/to/file2.pdf
```

- Merge the first page of each given file together:

```bash
pdfjoin path/to/file1.pdf path/to/file2.pdf ... 1 --outfile output_file
```

- Save pages 3 to 5 followed by page 1 to a new PDF with custom suffix:

```bash
pdfjoin path/to/file.pdf 3-5,1 --suffix rearranged
```

- Merge page subranges from two PDFs:

```bash
pdfjoin {/path/to/file1.pdf 2- file2 last-3 --outfile output_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Janek](mailto:27jf@pm.me) | pdfjoin: refresh (#5787) | 2021-06-07T21:44:02 | [0b828c566457](https://github.com/tldr-pages/tldr/commit/0b828c5664578bea5d7875b5bc580d75115ea389)
[Daniel Cervenkov](mailto:d.cervenkov@gmail.com) | pdfjoin: add page (#2040) | 2018-03-23T18:44:15 | [eeafea4b63e1](https://github.com/tldr-pages/tldr/commit/eeafea4b63e151e30e8e0c68ae041a8cf714be76)

