---
author: ['pxgamer', 'Seth Falco', 'Owen Voke']
date: 1656325392
title: "phploc, TLDR Pages"
description: "phploc, A tool for quickly measuring the size and analyzing the structure of a PHP project."
categories: "common"
---
> More information: <https://github.com/sebastianbergmann/phploc>.

- Analyze a directory and print the result:

```bash
phploc path/to/directory
```

- Include only specific files from a comma-separated list (globs are allowed):

```bash
phploc path/to/directory --names files
```

- Exclude specific files from a comma-separated list (globs are allowed):

```bash
phploc path/to/directory --names-exclude files
```

- Exclude a specific directory from analysis:

```bash
phploc path/to/directory --exclude path/to/exclude_directory
```

- Log the results to a specific CSV file:

```bash
phploc path/to/directory --log-csv path/to/file
```

- Log the results to a specific XML file:

```bash
phploc path/to/directory --log-xml path/to/file
```

- Count PHPUnit test case classes and test methods:

```bash
phploc path/to/directory --count-tests
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[pxgamer](mailto:owzie123@gmail.com) | phploc: add link to homepage | 2019-05-31T20:47:40 | [2c110be2e081](https://github.com/tldr-pages/tldr/commit/2c110be2e081dffc3c559fe50fff2f39d9785763)
[Owen Voke](mailto:owzie123@gmail.com) | phploc: add page (#2011) | 2018-03-01T18:46:36 | [64b2d40c0edc](https://github.com/tldr-pages/tldr/commit/64b2d40c0edc395539244299e9a03852e477d429)

