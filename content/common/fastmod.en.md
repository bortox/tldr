---
author: ['محمد الصوالحي']
date: 1646823518
title: "fastmod"
description: "fastmod, A fast partial replacement for the codemod tool, replace and replace all in the whole codebase."
categories: "common"
---
> Regexes are matched by Rust regex crate.

> More information: <https://github.com/facebookincubator/fastmod>.

- Replace a regex pattern in all files of the current directory, ignoring files on .ignore and .gitignore:

```bash
fastmod regex_pattern replacement
```

- Replace a regex pattern in case-insensitive mode in specific files or directories:

```bash
fastmod --ignore-case regex_pattern replacement -- path/to/file path/to/directory ...
```

- Replace a regex pattern in in a specific directory files filtered with a case-insensitive glob pattern:

```bash
fastmod regex replacement --dir path/to/directory --iglob '**/*.{js,json}'
```

- Replace for an exact string in .js or .json files:

```bash
fastmod --fixed-strings exact_string replacement --extensions json,js
```

- Replace for an exact string without prompt for a confirmation (disables regular expressions):

```bash
fastmod --accept-all --fixed-strings exact_string replacement
```

- Replace for an exact string without prompt for a confirmation, printing changed files:

```bash
fastmod --accept-all --print-changed-files --fixed-strings exact_string replacement
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[محمد الصوالحي](mailto:ms.2052001@gmail.com) | fastmod: add page (#7815) | 2022-03-09T11:58:38 | [37ab478d7988](https://github.com/tldr-pages/tldr/commit/37ab478d798855a43d0aea5f4e598825e30ec707)

