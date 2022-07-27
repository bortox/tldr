---
author: ['Waldir Pimenta', 'Srinivasan R', 'CARE-COLIN Thibaut', 'Ruben Vereecken', 'pxgamer', 'Sinan', 'Matthieu Oger', 'James H. Linder', 'Bertrand Delacretaz', 'Vivek Kalyan', 'Yurii Rochniak', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1648358715
title: "awk, TLDR Pages"
description: "awk, A versatile programming language for working on files."
categories: "common"
---
> More information: <https://github.com/onetrueawk/awk>.

- Print the fifth column (a.k.a. field) in a space-separated file:

```bash
awk '{print $5}' filename
```

- Print the second column of the lines containing "foo" in a space-separated file:

```bash
awk '/foo/ {print $2}' filename
```

- Print the last column of each line in a file, using a comma (instead of space) as a field separator:

```bash
awk -F ',' '{print $NF}' filename
```

- Sum the values in the first column of a file and print the total:

```bash
awk '{s+=$1} END {print s}' filename
```

- Print every third line starting from the first line:

```bash
awk 'NR%3==1' filename
```

- Print different values based on conditions:

```bash
awk '{if ($1 == "foo") print "Exact match foo"; else if ($1 ~ "bar") print "Partial match bar"; else print "Baz"}' filename
```

- Print all lines where the 10th column value equals the specified value:

```bash
awk '($10 == value)'
```

- Print all the lines which the 10th column value is between a min and a max:

```bash
awk '($10 >= min_value && $10 <= max_value)'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | awk: add operators match (#4606) | 2020-11-01T15:42:00 | [d78a7103fe7a](https://github.com/tldr-pages/tldr/commit/d78a7103fe7a55ee8ec04cd1ed8eea12f3dbb3a0)
[Vivek Kalyan](mailto:hello@vivekkalyan.com) | awk: simplify loop/fix missing filename (#3848) | 2020-02-17T22:26:27 | [897cff578dd2](https://github.com/tldr-pages/tldr/commit/897cff578dd2e3f0aefdffa10326a2c99afa42df)
[Yurii Rochniak](mailto:yrochnyak@gmail.com) | awk: add loops and conditions examples (#3300) | 2019-10-03T09:32:03 | [abbdb46c3b43](https://github.com/tldr-pages/tldr/commit/abbdb46c3b435ce6266dd70392654f5198bfb6db)
[pxgamer](mailto:owzie123@gmail.com) | awk: add link to homepage | 2019-06-09T18:53:49 | [9b992ed24e17](https://github.com/tldr-pages/tldr/commit/9b992ed24e17e927b7b1cc505184ad30879e6c84)
[Sinan](mailto:sbulutw@gmail.com) | awk: add print every nth line example (#2008) | 2018-02-23T07:05:11 | [2926835dd67f](https://github.com/tldr-pages/tldr/commit/2926835dd67fe4e352bb5e38bdd17fbedac5920a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | awk: introduce $NF (#956) Numbered field references have been used in the first two examples, so it's quite reasonable to take the [...] | 2016-07-16T14:30:28 | [6a988e932528](https://github.com/tldr-pages/tldr/commit/6a988e9325283efdbfc8d06e66901808750e2db8)
[Matthieu Oger](mailto:moger@pixelnest.io) | awk: add /search/ example | 2016-02-04T19:30:40 | [423d71f9e5cd](https://github.com/tldr-pages/tldr/commit/423d71f9e5cdf7a0e2ab05094f5aa84b33757176)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[Bertrand Delacretaz](mailto:bdelacretaz@apache.org) | sepearted -> separated | 2014-08-04T15:51:19 | [4c4995d77bba](https://github.com/tldr-pages/tldr/commit/4c4995d77bba43e3f385d62c1724a90ca8ac2295)
[James H. Linder](mailto:james@jlinder.com) | Adding a file for awk. | 2014-03-08T18:03:01 | [3c3031854755](https://github.com/tldr-pages/tldr/commit/3c3031854755d26afac5142fb3cc0df02ef9b919)

