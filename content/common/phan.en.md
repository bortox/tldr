---
author: ['Seth Falco', 'Owen Voke']
date: 1656325392
title: "phan, TLDR Pages"
description: "phan, A static analysis tool for PHP."
categories: "common"
---
> More information: <https://github.com/phan/phan>.

- Generate a `.phan/config.php` in the current directory:

```bash
phan --init
```

- Generate a Phan configuration file using a specific level (1 being strictest to 5 being the least strict):

```bash
phan --init --init-level level
```

- Analyze the current directory:

```bash
phan
```

- Analyze one or more directories:

```bash
phan --directory path/to/directory --directory path/to/another_directory
```

- Specify a config file (defaults to `.phan/config.php`):

```bash
phan --config-file path/to/config.php
```

- Specify the output mode:

```bash
phan --output-mode text|verbose|json|csv|codeclimate|checkstyle|pylint|html
```

- Specify the number of parallel processes:

```bash
phan --processes number_of_processes
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Owen Voke](mailto:development@voke.dev) | phan: add page (#4376) | 2020-10-02T13:01:32 | [5bb908c20549](https://github.com/tldr-pages/tldr/commit/5bb908c20549e6df890293ac3e23739880cfe241)

