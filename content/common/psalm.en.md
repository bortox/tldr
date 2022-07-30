---
author: ['Owen Voke', 'Seth Falco']
date: 1656325392
title: "psalm"
description: "psalm, A static analysis tool for finding errors in PHP applications."
categories: "common"
---
> More information: <https://psalm.dev>.

- Generate a Psalm configuration:

```bash
psalm --init
```

- Analyze the current working directory:

```bash
psalm
```

- Analyze a specific directory or file:

```bash
psalm path/to/file_or_directory
```

- Analyze a project with a specific configuration file:

```bash
psalm --config path/to/psalm.xml
```

- Include informational findings in the output:

```bash
psalm --show-info
```

- Analyze a project and display statistics:

```bash
psalm --stats
```

- Analyze a project in parallel with 4 threads:

```bash
psalm --threads 4
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Owen Voke](mailto:development@voke.dev) | psalm: add page (#5237) | 2021-02-05T17:54:29 | [981b7af185b7](https://github.com/tldr-pages/tldr/commit/981b7af185b74e31bcac0ab7bb7b3116b0fb412a)

