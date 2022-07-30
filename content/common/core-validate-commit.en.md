---
author: ['Axel Navarro']
date: 1642566633
title: "core-validate-commit"
description: "core-validate-commit, Validate commit messages for Node.js core."
categories: "common"
---
> More information: <https://github.com/nodejs/core-validate-commit>.

- Validate the current commit:

```bash
core-validate-commit
```

- Validate a specific commit:

```bash
core-validate-commit commit_hash
```

- Validate a range of commits:

```bash
git rev-list commit_hash..HEAD | xargs core-validate-commit
```

- List all validation rules:

```bash
core-validate-commit --list
```

- List all valid Node.js subsystems:

```bash
core-validate-commit --list-subsystem
```

- Validate the current commit formatting the output in tap format:

```bash
core-validate-commit --tap
```

- Display help:

```bash
core-validate-commit --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | core-validate-commit: add page (#7676) | 2022-01-19T05:30:33 | [c12b82906443](https://github.com/tldr-pages/tldr/commit/c12b82906443296ade3f70f35e6b71e6b847caaf)

