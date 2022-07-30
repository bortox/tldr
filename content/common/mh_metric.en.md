---
author: ['Axel Navarro']
date: 1648240038
title: "mh_metric"
description: "mh_metric, Calculate and enforce code metrics for MATLAB or Octave code."
categories: "common"
---
> More information: <https://misshit.org>.

- Print the code metrics for the specified files:

```bash
mh_metric path/to/file1.m path/to/file2.m ...
```

- Print the code metrics for the specified Octave files:

```bash
mh_metric --octave path/to/file1.m path/to/file2.m ...
```

- Print the code metrics for the specified directory recursively:

```bash
mh_metric path/to/directory
```

- Print the code metrics for the current directory:

```bash
mh_metric
```

- Print the code metrics report in HTML or JSON format:

```bash
mh_metric --html|json path/to/output_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | mh_metric: add page (#7912) | 2022-03-25T21:27:18 | [cd107da48b48](https://github.com/tldr-pages/tldr/commit/cd107da48b486527454e8ce8a9e6d31dc9b44c6a)

