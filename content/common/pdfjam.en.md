---
author: ['Janek']
date: 1620983025
title: "pdfjam"
description: "pdfjam, Shell frontend for the LaTeX pdfpages package for mingling PDFs."
categories: "common"
---
> More information: <https://github.com/rrthomas/pdfjam>.

- Merge two (or more) PDFs:

```bash
pdfjam path/to/file1.pdf path/to/file2.pdf --outfile path/to/output_file.pdf
```

- Merge the first page of each file together:

```bash
pdfjam files... 1 --outfile path/to/output_file.pdf
```

- Merge subranges from two PDFs:

```bash
pdfjam path/to/file1.pdf 3-5,1 path/to/file2.pdf 4-6 --outfile path/to/output_file.pdf
```

- Sign an A4 page (adjust delta to height for other formats) with a scanned signature by overlaying them:

```bash
pdfjam path/to/file.pdf path/to/signature --fitpaper true --outfile path/to/signed.pdf --nup "1x2" --delta "0 -842pt"
```

- Arrange the pages from the input file into a fancy 2x2 grid:

```bash
pdfjam path/to/file.pdf --nup 2x2 --suffix 4up --preamble '\usepackage{fancyhdr} \pagestyle{fancy}'
```

- Reverse the order of pages within each given file and concatenate them:

```bash
pdfjam files... last-1 --suffix reversed
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Janek](mailto:27jf@pm.me) | pdfjam: add page (#5789) | 2021-05-14T11:03:45 | [8f9dd1cd74ae](https://github.com/tldr-pages/tldr/commit/8f9dd1cd74ae28d196db2963fd3c2625ef3f3f61)

