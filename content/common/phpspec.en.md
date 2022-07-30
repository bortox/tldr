---
author: ['Owen Voke']
date: 1561460234
title: "phpspec"
description: "phpspec, A Behaviour Driven Development tool for PHP."
categories: "common"
---
> More information: <https://phpspec.net>.

- Create a specification for a class:

```bash
phpspec describe class_name
```

- Run all specifications in the "spec" directory:

```bash
phpspec run
```

- Run a single specification:

```bash
phpspec run path/to/class_specification_file
```

- Run specifications using a specific configuration file:

```bash
phpspec run -c path/to/configuration_file
```

- Run specifications using a specific bootstrap file:

```bash
phpspec run -b path/to/bootstrap_file
```

- Disable code generation prompts:

```bash
phpspec run --no-code-generation
```

- Enable fake return values:

```bash
phpspec run --fake
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:owzie123@gmail.com) | phpspec: add page (#3123) | 2019-06-25T12:57:14 | [731c5517643e](https://github.com/tldr-pages/tldr/commit/731c5517643e9020f6f60f4cc3a68d3787b153ad)

