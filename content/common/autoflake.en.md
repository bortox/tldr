---
author: ['Andrew Dassonville', 'Schneider', 'Marco Bonelli']
date: 1559564381
title: "autoflake"
description: "autoflake, A tool to remove unused imports and variables from Python code."
categories: "common"
---
> More information: <https://github.com/myint/autoflake>.

- Remove unused variables from a single file and display the diff:

```bash
autoflake --remove-unused-variables file.py
```

- Remove unused imports from multiple files and display the diffs:

```bash
autoflake --remove-all-unused-imports file1.py file2.py file3.py
```

- Remove unused variables from a file, overwriting the file:

```bash
autoflake --remove-unused-variables --in-place file.py
```

- Remove unused variables recursively from all files in a directory, overwriting each file:

```bash
autoflake --remove-unused-variables --in-place --recursive path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | autoflake.md: add homepage | 2019-04-12T14:41:22 | [e32b32063586](https://github.com/tldr-pages/tldr/commit/e32b32063586e090ad638fcee0e3463f62ebeaed)
[Andrew Dassonville](mailto:dassonville.andrew@gmail.com) | autoflake: add page (#1853) | 2018-01-02T11:33:12 | [b8d0eaa03ef2](https://github.com/tldr-pages/tldr/commit/b8d0eaa03ef2cb1744948eb56abae9eb95ac3534)

