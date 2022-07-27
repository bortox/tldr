---
author: ['Emma Bukacek', 'marchersimon']
date: 1618756407
title: "complete, TLDR Pages"
description: "complete, Provides argument autocompletion to shell commands."
categories: "common"
---
> More information: <https://www.gnu.org/software/bash/manual/html_node/Programmable-Completion-Builtins.html>.

- Apply a function that performs autocompletion to a command:

```bash
complete -F function command
```

- Apply a command that performs autocompletion to another command:

```bash
complete -C autocomplete_command command
```

- Apply autocompletion without appending a space to the completed word:

```bash
complete -o nospace -F function command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | complete: add link | 2021-04-18T16:33:27 | [02f8ccffbede](https://github.com/tldr-pages/tldr/commit/02f8ccffbede5fe1feac284569e1f8a9ee917e09)
[Emma Bukacek](mailto:emma.bukacek@gmail.com) | complete: add page (#2136) | 2018-06-11T21:19:27 | [dfabca0566f4](https://github.com/tldr-pages/tldr/commit/dfabca0566f468fc842c527e5ba621effa40b4e6)

