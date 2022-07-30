---
author: ['Paul Somers']
date: 1648647902
title: "gt"
description: "gt, Create and manage sequences of dependent code changes (stacks) for Git and GitHub."
categories: "common"
---
> More information: <https://docs.graphite.dev>.

- Authenticate the CLI with Graphite's API:

```bash
gt auth --token graphite_cli_auth_token
```

- Initialise `gt` for the repository in the current directory:

```bash
gt repo init
```

- Create a new branch stacked on top of the current branch and commit staged changes:

```bash
gt branch create branch_name
```

- Create a new commit and fix upstack branches:

```bash
gt commit create -m commit_message
```

- Force push all branches in the current stack to GitHub and create or update PRs:

```bash
gt stack submit
```

- Log all tracked stacks:

```bash
gt log short
```

- Print help for a specified subcommand:

```bash
gt subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Paul Somers](mailto:paulsomers@gmail.com) | gt: add page (#7926) * gt: add page graphite.dev * gt: fix review suggestions Co-authored-by: Axel Navarro <navarroaxel@gmail.com> * [...] | 2022-03-30T15:45:02 | [a456da282272](https://github.com/tldr-pages/tldr/commit/a456da282272c5b66363749179e44f120a73afab)

