---
author: ['Owen Voke', 'pxgamer', 'Seth Falco']
date: 1656325392
title: "phpstan"
description: "phpstan, A PHP static analysis tool to discover bugs in code."
categories: "common"
---
> More information: <https://github.com/phpstan/phpstan>.

- Display available options for analysis:

```bash
phpstan analyse --help
```

- Analyze the specified space-separated directories:

```bash
phpstan analyse path/to/directory
```

- Analyze a directory using a configuration file:

```bash
phpstan analyse path/to/directory --configuration path/to/config
```

- Analyze using a specific rule level (0-7, higher is stricter):

```bash
phpstan analyse path/to/directory --level level
```

- Specify an autoload file to load before analyzing:

```bash
phpstan analyse path/to/directory --autoload-file path/to/autoload_file
```

- Specify a memory limit during analysis:

```bash
phpstan analyse path/to/directory --memory-limit memory_limit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[pxgamer](mailto:owzie123@gmail.com) | phpstan: add link to homepage | 2019-05-31T20:47:40 | [64337ef54eaf](https://github.com/tldr-pages/tldr/commit/64337ef54eaf1583ad485403aa15309ceb4ecf35)
[Owen Voke](mailto:owzie123@gmail.com) | phpstan: add page (#2009) | 2018-02-28T22:43:29 | [1eab1cf2913f](https://github.com/tldr-pages/tldr/commit/1eab1cf2913f9930de7eeb2cab4fb9c36215a949)

