---
author: ['Axel Navarro']
date: 1610529931
title: "gh completion"
description: "gh completion, Generate shell completion scripts for GitHub CLI commands."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_completion>.

- Display the subcommand help:

```bash
gh completion
```

- Print a completion script:

```bash
gh completion --shell bash|zsh|fish|powershell
```

- Append the `gh` completion script to `~/.bashrc`:

```bash
gh completion --shell bash >> ~/.bashrc
```

- Append the `gh` completion script to `~/.zshrc`:

```bash
gh completion --shell zsh >> ~/.zshrc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-completion: add page (#5134) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-01-13T10:25:31 | [b96212241574](https://github.com/tldr-pages/tldr/commit/b96212241574f439b418056fa02be99f197a5380)

