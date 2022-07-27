---
author: ['Daniel Birket']
date: 1627399924
title: "ffe, TLDR Pages"
description: "ffe, Extract fields from a flat database file and write to another format."
categories: "common"
---
> A configuration file is required to interpret the input and format the output.

> More information: <http://ff-extractor.sourceforge.net/ffe.html>.

- Display all input data using the specified data configuration:

```bash
ffe --configuration=path/to/config.ffe path/to/input
```

- Convert an input file to an output file in a new format:

```bash
ffe --output=path/to/output -c path/to/config.ffe path/to/input
```

- Select input structure and print format from definitions in `~/.fferc` config file:

```bash
ffe --structure=structure --print=format path/to/input
```

- Write only the selected fields:

```bash
ffe --field-list="FirstName,LastName,Age" -c path/to/config.ffe path/to/input
```

- Write only the records that match an expression:

```bash
ffe -e "LastName=Smith" -c path/to/config.ffe path/to/input
```

- Display help:

```bash
ffe --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | ffe: add page (#6261) * ffe: add page * ffe: changes following review comments - Clarified required default or specific configuration [...] | 2021-07-27T17:32:04 | [83cb0c5cd7a3](https://github.com/tldr-pages/tldr/commit/83cb0c5cd7a382dafe4298607c51de82db805fbc)

