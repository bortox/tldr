---
author: ['Chris Winberry']
date: 1603125537
title: "csvtool, TLDR Pages"
description: "csvtool, Utility to filter and extract data from CSV formatted sources."
categories: "common"
---
> More information: <https://github.com/maroofi/csvtool>.

- Extract the second column from a CSV file:

```bash
csvtool --column 2 path/to/file.csv
```

- Extract the second and fourth columns from a CSV file:

```bash
csvtool --column 2,4 path/to/file.csv
```

- Extract lines from a CSV file where the second column exactly matches 'Foo':

```bash
csvtool --column 2 --search '^Foo$' path/to/file.csv
```

- Extract lines from a CSV file where the second column starts with 'Bar':

```bash
csvtool --column 2 --search '^Bar' path/to/file.csv
```

- Find lines in a CSV file where the second column ends with 'Baz' and then extract the third and sixth columns:

```bash
csvtool --column 2 --search 'Baz$' path/to/file.csv | csvtool --no-header --column 3,6
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Chris Winberry](mailto:tautologistics@users.noreply.github.com) | csvtool: add page (#4391) | 2020-10-19T18:38:57 | [844675fdb0ea](https://github.com/tldr-pages/tldr/commit/844675fdb0ea515e7030ed055e32ebdd455a8782)

