---
author: ['Choi Young-jin', 'John Toohey']
date: 1652957013
title: "prettier"
description: "prettier, An opinionated code formatter for JavaScript, JSON, CSS, YAML, and more."
categories: "common"
---
> More information: <https://prettier.io/>.

- Format a file and print the result to stdout:

```bash
prettier path/to/file
```

- Check if a specific file has been formatted:

```bash
prettier --check path/to/file
```

- Run with a specific configuration file:

```bash
prettier --config path/to/config_file path/to/file
```

- Format a file or directory, replacing the original:

```bash
prettier --write path/to/file_or_directory
```

- Format files or directories recursively using single quotes and no trailing commas:

```bash
prettier --single-quote --trailing-comma none --write path/to/file_or_directory
```

- Format JavaScript and TypeScript files recursively, replacing the original:

```bash
prettier --write "**/*.{js,jsx,ts,tsx}"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | prettier: add --write example for js and ts files (#8069) | 2022-05-19T12:43:33 | [715be54612be](https://github.com/tldr-pages/tldr/commit/715be54612beb1c38725bf193415b32efe236d50)
[John Toohey](mailto:john_t@mailo.com) | prettier: add page (#6192) | 2021-07-14T21:58:53 | [37e4ef76960e](https://github.com/tldr-pages/tldr/commit/37e4ef76960ea6b1cc14832e4b44fb93f04c9206)

