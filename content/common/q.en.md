---
author: ['Waldir Pimenta', 'Lucas Gabriel Schneider', 'Dan Kim', 'pxgamer', 'HairyFotr']
date: 1612112718
title: "q"
description: "q, Execute SQL-like queries on .csv and .tsv files."
categories: "common"
---
> More information: <https://harelba.github.io/q>.

- Query `.csv` file by specifying the delimiter as ',':

```bash
q -d',' "SELECT * from path/to/file"
```

- Query `.tsv` file:

```bash
q -t "SELECT * from path/to/file"
```

- Query file with header row:

```bash
q -ddelimiter -H "SELECT * from path/to/file"
```

- Read data from stdin; '-' in the query represents the data from stdin:

```bash
output | q "select * from -"
```

- Join two files (aliased as `f1` and `f2` in the example) on column `c1`, a common column:

```bash
q "SELECT * FROM path/to/file f1 JOIN path/to/other_file f2 ON (f1.c1 = f2.c1)"
```

- Format output using an output delimiter with an output header line (note: command will output column names based on the input file header or the column aliases overridden in the query):

```bash
q -Ddelimiter -O "SELECT column as alias from path/to/file"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | q: add link to homepage | 2019-05-29T14:41:10 | [bbd216de2bbf](https://github.com/tldr-pages/tldr/commit/bbd216de2bbfeb63111bdd8e883440885a6cc2f1)
[HairyFotr](mailto:hairyfotr@gmail.com) | Fix a few typos | 2017-07-23T16:22:44 | [e0ccb7147a25](https://github.com/tldr-pages/tldr/commit/e0ccb7147a25b5d738e3991f399f87e45f3a4140)
[Dan Kim](mailto:deekim@users.noreply.github.com) | q: add page (#1143) | 2016-11-05T19:39:47 | [c32263f9dca7](https://github.com/tldr-pages/tldr/commit/c32263f9dca77bf528a02c0e17eab206fdd936f7)

