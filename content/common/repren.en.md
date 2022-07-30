---
author: ['Starbeamrainbowlabs', 'Seth Falco', 'Marco Bonelli']
date: 1629050349
title: "repren"
description: "repren, Multi-pattern string replacement and file renaming tool."
categories: "common"
---
> More information: <https://github.com/jlevy/repren>.

- Do a dry-run renaming a directory of PNGs with a literal string replacement:

```bash
repren --dry-run --rename --literal --from 'find_string' --to 'replacement_string' *.png
```

- Do a dry-run renaming a directory of JPEGs with a regular expression:

```bash
repren --rename --dry-run --from 'regular_expression' --to 'replacement_string' *.jpg *.jpeg
```

- Do a find-and-replace on the contents of a directory of CSV files:

```bash
repren --from '([0-9]+) example_string' --to 'replacement_string \1' *.csv
```

- Do both a find-and-replace and a rename operation at the same time, using a pattern file:

```bash
repren --patterns path/to/patfile.ext --full *.txt
```

- Do a case-insensitive rename:

```bash
repren --rename --insensitive --patterns path/to/patfile.ext *
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: fix syntax | 2019-02-03T01:28:36 | [334c0b4fa3ea](https://github.com/tldr-pages/tldr/commit/334c0b4fa3ea6f24c50d62061db9075125cc608b)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | repren: add homepage | 2019-02-03T01:28:36 | [2b3bc4ac8184](https://github.com/tldr-pages/tldr/commit/2b3bc4ac8184f63bb8192ba6b8ab240b5b1a5472)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | repren: add page (#2054) | 2018-04-05T09:48:14 | [781d06a102d9](https://github.com/tldr-pages/tldr/commit/781d06a102d9c860ff66be0be496c599a1420326)

