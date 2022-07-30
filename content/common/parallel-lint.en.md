---
author: ['Owen Voke']
date: 1561476951
title: "parallel-lint"
description: "parallel-lint, A tool to check the syntax of PHP files in parallel."
categories: "common"
---
> More information: <https://github.com/JakubOnderka/PHP-Parallel-Lint>.

- Lint a specific directory:

```bash
parallel-lint path/to/directory
```

- Lint a directory using the specified number of parallel processes:

```bash
parallel-lint -j processes path/to/directory
```

- Lint a directory, excluding the specified directory:

```bash
parallel-lint --exclude path/to/excluded_directory path/to/directory
```

- Lint a directory of files using a comma-separated list of extension(s):

```bash
parallel-lint -e php,html,phpt path/to/directory
```

- Lint a directory and output the results as JSON:

```bash
parallel-lint --json path/to/directory
```

- Lint a directory and show Git Blame results for rows containing errors:

```bash
parallel-lint --blame path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:owzie123@gmail.com) | parallel-lint: add page (#3127) | 2019-06-25T17:35:51 | [5968eaa1edfb](https://github.com/tldr-pages/tldr/commit/5968eaa1edfb93c6df58deacb758ccdbe5374c26)

