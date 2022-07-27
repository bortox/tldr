---
author: ['Noy', 'stets', 'Francesco Franchina']
date: 1635360802
title: "black, TLDR Pages"
description: "black, A Python auto code formatter."
categories: "common"
---
> More information: <https://github.com/psf/black>.

- Auto-format a file or entire directory:

```bash
black path/to/file_or_directory
```

- Format the code passed in as a string:

```bash
black -c "code"
```

- Output the changes that would be applied for each file:

```bash
black --diff path/to/file_or_directory
```

- Perform a dry run (print what would be done without actually doing it):

```bash
black --check path/to/file_or_directory
```

- Auto-format a file or directory emitting exclusively error messages to stderr:

```bash
black --quiet path/to/file_or_directory
```

- Auto-format a file or directory without replacing single quotes with double quotes (adoption helper, avoid using this for new projects):

```bash
black --skip-string-normalization path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Francesco Franchina](mailto:cescus92@gmail.com) | black: making the description more consistent with other commands Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-10-27T20:53:22 | [e1ef02a1fd0e](https://github.com/tldr-pages/tldr/commit/e1ef02a1fd0e5caa672a6fcb195a33fc81786e6c)
[Francesco Franchina](mailto:cescus92@gmail.com) | black, python: improved clarity of some statements | 2021-10-27T20:53:22 | [5fed7f9bc728](https://github.com/tldr-pages/tldr/commit/5fed7f9bc728a809a6bf5f4f961a0567d6d33e25)
[Noy](mailto:noah.altunian@motorolasolutions.com) | black: add --skip-string-normalization example (#6517) | 2021-09-17T22:07:20 | [153c6d13bc4c](https://github.com/tldr-pages/tldr/commit/153c6d13bc4c485df335860b434b5635d2485791)
[stets](mailto:stetsblake@gmail.com) | black: add page (#3506) | 2019-10-31T02:29:02 | [eb8015a1922c](https://github.com/tldr-pages/tldr/commit/eb8015a1922c8edd6f51cc56b10f97f60f83e2ec)

