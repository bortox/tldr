---
author: ['Owen Voke', 'Waldir Pimenta', 'pxgamer', 'Lucas Gabriel Schneider']
date: 1612112718
title: "json5"
description: "json5, A command-line tool for converting JSON5 files to JSON."
categories: "common"
---
> More information: <https://json5.org>.

- Convert JSON5 stdin to JSON stdout:

```bash
echo input | json5
```

- Convert a JSON5 file to JSON and output to stdout:

```bash
json5 path/to/input_file.json5
```

- Convert a JSON5 file to the specified JSON file:

```bash
json5 path/to/input_file.json5 --out-file path/to/output_file.json
```

- Validate a JSON5 file:

```bash
json5 path/to/input_file.json5 --validate
```

- Specify the number of spaces to indent by (or "t" for tabs):

```bash
json5 --space indent_amount
```

- View available options:

```bash
json5 --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | json5: add link to homepage | 2019-06-06T04:42:48 | [9fb4d6b96ff7](https://github.com/tldr-pages/tldr/commit/9fb4d6b96ff7a8b624d354b0ef163fdb63675992)
[Owen Voke](mailto:owzie123@gmail.com) | json5: add page (#2024) | 2018-03-12T19:53:35 | [c94670d8ead4](https://github.com/tldr-pages/tldr/commit/c94670d8ead4b6d56234d3205447138119bc622c)

