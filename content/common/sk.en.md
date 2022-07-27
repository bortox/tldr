---
author: ['Muhammad Falak R Wani']
date: 1623348057
title: "sk, TLDR Pages"
description: "sk, Fuzzy finder written in Rust."
categories: "common"
---
> Similar to `fzf`.

> More information: <https://github.com/lotabout/skim>.

- Start skim on all files in the specified directory:

```bash
find path/to/directory -type f | sk
```

- Start skim for running processes:

```bash
ps aux | sk
```

- Start skim with a specified query:

```bash
sk --query "query"
```

- Select multiple files with `Shift + Tab` and write to a file:

```bash
find path/to/directory -type f | sk --multi > filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | skim: add page (#6081) Signed-off-by: Muhammad Falak R Wani <falakreyaz@gmail.com> Co-authored-by: Axel Navarro [...] | 2021-06-10T20:00:57 | [d6ad312c5fa0](https://github.com/tldr-pages/tldr/commit/d6ad312c5fa031d385109f7faee26964af8acec3)

