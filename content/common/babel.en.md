---
author: ['Waldir Pimenta', 'Schneider', 'Owen Voke', 'Lucas Gabriel Schneider', 'Marco Bonelli']
date: 1612112718
title: "babel"
description: "babel, A transpiler which converts code from JavaScript ES6/ES7 syntax to ES5 syntax."
categories: "common"
---
> More information: <https://babeljs.io/>.

- Transpile a specified input file and output to stdout:

```bash
babel path/to/file
```

- Transpile a specified input file and output to a specific file:

```bash
babel path/to/input_file --out-file path/to/output_file
```

- Transpile the input file every time it is changed:

```bash
babel path/to/input_file --watch
```

- Transpile a whole directory of files:

```bash
babel path/to/input_directory
```

- Ignore specified comma-separated files in a directory:

```bash
babel path/to/input_directory --ignore ignored_files
```

- Transpile and output as minified JavaScript:

```bash
babel path/to/input_file --minified
```

- Choose a set of presets for output formatting:

```bash
babel path/to/input_file --presets presets
```

- Output all available options:

```bash
babel --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | babel.md: add status | 2019-04-12T14:41:22 | [e0812891a47c](https://github.com/tldr-pages/tldr/commit/e0812891a47c74bc24b484ade713977041bf8c1b)
[Owen Voke](mailto:owzie123@gmail.com) | babel: add page (#1944) | 2018-02-12T23:19:25 | [60c61f97ff09](https://github.com/tldr-pages/tldr/commit/60c61f97ff09b3542fca99094dbf69d9d04d0736)

