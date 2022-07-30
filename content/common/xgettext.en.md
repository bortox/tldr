---
author: ['Pierre Rudloff']
date: 1575123394
title: "xgettext"
description: "xgettext, Extract gettext strings from code files."
categories: "common"
---
> More information: <https://www.gnu.org/software/gettext/manual/html_node/xgettext-Invocation.html>.

- Scan file and output strings to `messages.po`:

```bash
xgettext path/to/input_file
```

- Use a different output filename:

```bash
xgettext --output path/to/output_file path/to/input_file
```

- Append new strings to an existing file:

```bash
xgettext --join-existing --output path/to/output_file path/to/input_file
```

- Don't add a header containing metadata to the output file:

```bash
xgettext --omit-header path/to/input_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | xgettext: add page (#3635) | 2019-11-30T15:16:34 | [30a42690188e](https://github.com/tldr-pages/tldr/commit/30a42690188e32c74eceb52db55d83de289d514a)

