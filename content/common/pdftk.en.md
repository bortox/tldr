---
author: ['frinkelpi', 'pxgamer', 'David Husz', 'Marco Bonelli']
date: 1593982304
title: "pdftk"
description: "pdftk, PDF toolkit."
categories: "common"
---
> More information: <https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit>.

- Extract pages 1-3, 5 and 6-10 from a PDF file and save them as another one:

```bash
pdftk input.pdf cat 1-3 5 6-10 output output.pdf
```

- Merge (concatenate) a list of PDF files and save the result as another one:

```bash
pdftk file1.pdf file2.pdf ... cat output output.pdf
```

- Split each page of a PDF file into a separate file, with a given filename output pattern:

```bash
pdftk input.pdf burst output out_%d.pdf
```

- Rotate all pages by 180 degrees clockwise:

```bash
pdftk input.pdf cat 1-endsouth output output.pdf
```

- Rotate third page by 90 degrees clockwise and leave others unchanged:

```bash
pdftk input.pdf cat 1-2 3east 4-end output output.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[David Husz](mailto:61841263+davidhusz@users.noreply.github.com) | pdftk: avoid non-ascii characters (#4144) | 2020-07-05T22:51:44 | [3a516641b597](https://github.com/tldr-pages/tldr/commit/3a516641b597dff5570d56f549041e16fb6e4c61)
[pxgamer](mailto:owzie123@gmail.com) | pdftk: add link to homepage | 2019-05-31T20:47:40 | [1d15900d0fa8](https://github.com/tldr-pages/tldr/commit/1d15900d0fa83acdc7368ef8d6223321332fea83)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | nmap, pdftk, samtools, tig: ellipsis consistency. | 2019-02-03T04:27:37 | [1799a53d7876](https://github.com/tldr-pages/tldr/commit/1799a53d7876f1abb9ddcd1eb33cd2ca6df745ca)
[frinkelpi](mailto:frinkelpi@users.noreply.github.com) | pdftk: add page (#1126) | 2016-10-24T18:16:49 | [0f8f19cfc662](https://github.com/tldr-pages/tldr/commit/0f8f19cfc6625560f684587576012b47095a69f0)

