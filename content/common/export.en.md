---
author: ['marchersimon']
date: 1631539482
title: "export"
description: "export, Command to mark shell variables in the current environment to be exported with any newly forked child processes."
categories: "common"
---
> More information: <https://www.gnu.org/software/bash/manual/bash.html#index-export>.

- Set a new environment variable:

```bash
export VARIABLE=value
```

- Remove an environment variable:

```bash
export -n VARIABLE
```

- Mark a shell function for export:

```bash
export -f FUNCTION_NAME
```

- Append something to the PATH variable:

```bash
export PATH=$PATH:path/to/append
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | compgen, eval, export, file: move to common (#6508) | 2021-09-13T15:24:42 | [ac46610ce633](https://github.com/tldr-pages/tldr/commit/ac46610ce6338c5a56328c69fbe047a08d663d78)

