---
author: ['Axel Navarro']
date: 1619541749
title: "kate"
description: "kate, KDE Text Editor."
categories: "common"
---
> More information: <https://kate-editor.org/>.

- Launch Kate and open specific files:

```bash
kate path/to/file1 path/to/file2
```

- Open a remote document in Kate:

```bash
kate https://example.com/path/to/file
```

- Launch Kate, creating a new instance even if one is already open:

```bash
kate --new
```

- Open a file in Kate with the cursor at the specific line:

```bash
kate --line line_number path/to/file
```

- Open a file in Kate with the cursor at the specific line and column:

```bash
kate --line line_number --column column_number path/to/file
```

- Launch Kate, creating a new temporary file with contents read from stdin:

```bash
cat path/to/file | kate --stdin
```

- Display help:

```bash
kate --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | kate: improve remote document example (#5842) | 2021-04-27T18:42:29 | [d08f5ebefce8](https://github.com/tldr-pages/tldr/commit/d08f5ebefce8ea37739d37a71c25abb0a3544ad5)
[Axel Navarro](mailto:navarroaxel@gmail.com) | kate: add page (#5834) * kate: add page * Replace --tempfile with --column example * Update pages/common/kate.md Co-authored-by: bl-ue [...] | 2021-04-27T18:00:35 | [051ec5e29af5](https://github.com/tldr-pages/tldr/commit/051ec5e29af54e80c5b96f5910e23adf69d7a6da)

