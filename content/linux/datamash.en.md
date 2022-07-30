---
author: ['Niccolò Maggioni', 'Stig124']
date: 1625841955
title: "datamash"
description: "datamash, Tool to perform basic numeric, textual and statistical operations on input textual data files."
categories: "linux"
---
> More information: <http://www.gnu.org/software/datamash/>.

- Get max, min, mean and median of a single column of numbers:

```bash
seq 3 | datamash max 1 min 1 mean 1 median 1
```

- Get the mean of a single column of float numbers (floats must use "," and not "."):

```bash
echo -e '1.0\n2.5\n3.1\n4.3\n5.6\n5.7' | tr '.' ',' | datamash mean 1
```

- Get the mean of a single column of numbers with a given decimal precision:

```bash
echo -e '1\n2\n3\n4\n5\n5' | datamash -R number_of_decimals_wanted mean 1
```

- Get the mean of a single column of numbers ignoring "Na" and "NaN" (literal) strings:

```bash
echo -e '1\n2\nNa\n3\nNaN' | datamash --narm mean 1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Niccolò Maggioni](mailto:nicco.maggioni@gmail.com) | datamash: add page (#2085) | 2018-05-02T12:01:05 | [4033673bc6c8](https://github.com/tldr-pages/tldr/commit/4033673bc6c851fec7d7b6b1c88e4f1250f0ff16)

