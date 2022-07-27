---
author: ['Martin Pool']
date: 1645706554
title: "chsh, TLDR Pages"
description: "chsh, Change the user's login shell."
categories: "linux"
---
> More information: <https://manned.org/chsh>.

- Change the current user's login shell interactively:

```bash
chsh
```

- Change the current user's login shell:

```bash
chsh --shell path/to/shell
```

- Change the login shell for a given user:

```bash
chsh --shell path/to/shell username
```

- List available shells:

```bash
chsh --list-shells
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Martin Pool](mailto:mbp@sourcefrog.net) | chsh: Fix `chsh -s SHELL` syntax (#7801) * It's `ch -s SHELL` to change your own shell Fixes #7800 * rephrase Co-authored-by: [...] | 2022-02-24T13:42:34 | [326cc8a262cb](https://github.com/tldr-pages/tldr/commit/326cc8a262cbad579a1f1f858df768c00eb46518)

