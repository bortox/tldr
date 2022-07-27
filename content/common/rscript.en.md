---
author: ['Josh Cook']
date: 1633269062
title: "Rscript, TLDR Pages"
description: "Rscript, Run a script with the R programming language."
categories: "common"
---
> More information: <https://www.r-project.org>.

- Run a script:

```bash
Rscript path/to/file.R
```

- Run a script in vanilla mode (i.e. a blank session that doesn't save the workspace at the end):

```bash
Rscript --vanilla path/to/file.R
```

- Execute one or more R expressions:

```bash
Rscript -e expression1 -e expression2
```

- Display R version:

```bash
Rscript --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Josh Cook](mailto:39419448+jhrcook@users.noreply.github.com) | rscript: add page (#6686) | 2021-10-03T15:51:02 | [6b5364ce2f09](https://github.com/tldr-pages/tldr/commit/6b5364ce2f09ab392765f668bf02ca22c7fd527a)

