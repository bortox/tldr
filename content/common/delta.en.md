---
author: ['Axel Navarro', 'lucas schneider']
date: 1610111394
title: "delta"
description: "delta, A viewer for Git and diff output."
categories: "common"
---
> More information: <https://github.com/dandavison/delta>.

- Compare files or directories:

```bash
delta path/to/old_file_or_directory path/to/new_file_or_directory
```

- Compare files or directories, showing the line numbers:

```bash
delta --line-numbers path/to/old_file_or_directory path/to/new_file_or_directory
```

- Compare files or directories, showing the differences side by side:

```bash
delta --side-by-side path/to/old_file_or_directory path/to/new_file_or_directory
```

- Compare files or directories, ignoring any Git configuration settings:

```bash
delta --no-gitconfig path/to/old_file_or_directory path/to/new_file_or_directory
```

- Compare, rendering commit hashes, file names, and line numbers as hyperlinks, according to the hyperlink spec for terminal emulators:

```bash
delta --hyperlinks path/to/old_file_or_directory path/to/new_file_or_directory
```

- Display the current settings:

```bash
delta --show-config
```

- Display supported languages and associated file extensions:

```bash
delta --list-languages
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Axel Navarro](mailto:navarroaxel@gmail.com) | delta: add page (#4317) | 2020-09-11T13:00:42 | [693ff4a00df7](https://github.com/tldr-pages/tldr/commit/693ff4a00df7d9736bd3214162c6d8ee2599503b)

