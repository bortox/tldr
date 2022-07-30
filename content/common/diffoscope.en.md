---
author: ['Juri', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629050349
title: "diffoscope"
description: "diffoscope, Compare files, archives, and directories."
categories: "common"
---
> More information: <https://diffoscope.org>.

- Compare two files:

```bash
diffoscope path/to/file1 path/to/file2
```

- Compare two files without displaying a progress bar:

```bash
diffoscope --no-progress path/to/file1 path/to/file2
```

- Compare two files and write an HTML-report to a file (use `-` for stdout):

```bash
diffoscope --html path/to/outfile|- path/to/file1 path/to/file2
```

- Compare two directories excluding files with a name matching a specified pattern:

```bash
diffoscope --exclude pattern path/to/directory1 path/to/directory2
```

- Compare two directories and control whether directory metadata is considered:

```bash
diffoscope --exclude-directory-metadata auto|yes|no|recursive path/to/directory1 path/to/directory2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Juri](mailto:juri.dispan@posteo.net) | diffoscope: add page (#4660) | 2020-10-13T00:17:16 | [bed0832734a2](https://github.com/tldr-pages/tldr/commit/bed0832734a28ce6d2cf9ea7fdaf2bb583c58614)

