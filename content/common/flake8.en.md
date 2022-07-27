---
author: ['Macklan Weinstein']
date: 1628208887
title: "flake8, TLDR Pages"
description: "flake8, Tool to check the style and quality of Python code."
categories: "common"
---
> More information: <https://flake8.pycqa.org/>.

- Lint a file or directory recursively:

```bash
flake8 path/to/file_or_directory
```

- Lint a file or directory recursively and show the line on which each error occurred:

```bash
flake8 --show-source path/to/file_or_directory
```

- Lint a file or directory recursively and ignore a list of rules. (All available rules can be found at flake8rules.com):

```bash
flake8 --ignore rule1,rule2 path/to/file_or_directory
```

- Lint a file or directory recursively but exclude files matching the given globs or substrings:

```bash
flake8 --exclude substring1,glob2 path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Macklan Weinstein](mailto:wolfgang.wazzle.strauss@gmail.com) | flake8: add page (#6275) | 2021-08-06T02:14:47 | [3d7dd2169eab](https://github.com/tldr-pages/tldr/commit/3d7dd2169eab7ae94313485554334e4d8849bc66)

