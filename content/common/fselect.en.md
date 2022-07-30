---
author: ['Philipp Weißmann']
date: 1559674123
title: "fselect"
description: "fselect, Find files with SQL-like queries."
categories: "common"
---
> More information: <https://github.com/jhspetersson/fselect>.

- Select full path and size from temporary or config files in a given directory:

```bash
fselect size, path from path/to/directory where name = '*.cfg' or name = '*.tmp'
```

- Find square images:

```bash
fselect path from path/to/directory where width = height
```

- Find old-school rap 320kbps MP3 files:

```bash
fselect path from path/to/directory where genre = Rap and bitrate = 320 and mp3_year lt 2000
```

- Select only the first 5 results and output as JSON:

```bash
fselect size, path from path/to/directory limit 5 into json
```

- Use SQL aggregate functions to calculate minimum, maximum and average size of files in a directory:

```bash
fselect "MIN(size), MAX(size), AVG(size), SUM(size), COUNT(*) from path/to/directory"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Philipp Weißmann](mailto:github@philipp-weissmann.de) | fselect: add page (#2975) | 2019-06-04T20:48:43 | [a551be0b2a0d](https://github.com/tldr-pages/tldr/commit/a551be0b2a0d0ab879a3ce95e3642e689463652c)

