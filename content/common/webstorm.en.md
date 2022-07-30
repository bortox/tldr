---
author: ['Axel Navarro']
date: 1643764061
title: "webstorm"
description: "webstorm, The JetBrains JavaScript IDE."
categories: "common"
---
> More information: <https://www.jetbrains.com/help/webstorm/working-with-the-ide-features-from-command-line.html>.

- Open the current directory in WebStorm:

```bash
webstorm
```

- Open a specific directory in WebStorm:

```bash
webstorm path/to/directory
```

- Open specific files in the LightEdit mode﻿:

```bash
webstorm -e path/to/file1 path/to/file2 ...
```

- Open and wait until done editing a specific file in the LightEdit mode:

```bash
webstorm --wait -e path/to/file
```

- Open a file with the cursor at the specific line:

```bash
webstorm --line line_number path/to/file
```

- Open and compare files (supports up to 3 files):

```bash
webstorm diff path/to/file1 path/to/file2
```

- Open and perform a three-way merge:

```bash
webstorm merge path/to/left_file path/to/right_file path/to/target_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | webstorm: add page (#7727) | 2022-02-02T02:07:41 | [da55f621eb9c](https://github.com/tldr-pages/tldr/commit/da55f621eb9c77d579b4353d78cc4c9bec39c4f3)

