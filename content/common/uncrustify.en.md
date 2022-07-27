---
author: ['Starbeamrainbowlabs']
date: 1583945456
title: "uncrustify, TLDR Pages"
description: "uncrustify, C, C++, C#, D, Java and Pawn source code formatter."
categories: "common"
---
> More information: <https://github.com/uncrustify/uncrustify>.

- Format a single file:

```bash
uncrustify -f path/to/file.cpp -o path/to/output.cpp
```

- Read filenames from stdin, and take backups before writing output back to the original filepaths:

```bash
find . -name "*.cpp" | uncrustify -F - --replace
```

- Don't make backups (useful if files are under version control):

```bash
find . -name "*.cpp" | uncrustify -F - --no-backup
```

- Use a custom configuration file and write the result to stdout:

```bash
uncrustify -c path/to/uncrustify.cfg -f path/to/file.cpp
```

- Explicitly set a configuration variable's value:

```bash
uncrustify --set option=value
```

- Generate a new configuration file:

```bash
uncrustify --update-config -o path/to/new.cfg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | uncrustify: add page (#3904) | 2020-03-11T17:50:56 | [cd056a4b5b72](https://github.com/tldr-pages/tldr/commit/cd056a4b5b72f0c2ed20f6af11f2f5cf782c5cfe)

