---
author: ['Axel Navarro']
date: 1635955709
title: "gh codespace"
description: "gh codespace, Connect and manage your codespaces in GitHub."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_codespace>.

- Create a codespace in GitHub interactively:

```bash
gh codespace create
```

- List all available codespaces:

```bash
gh codespace list
```

- Connect to a codespace via SSH interactively:

```bash
gh codespace ssh
```

- Transfer a file to a codespace interactively:

```bash
gh codespace cp path/to/source_file remote:path/to/remote_file
```

- List the ports of a codespace interactively:

```bash
gh codespace ports
```

- Print the logs from a codespace interactively:

```bash
gh codespace logs
```

- Delete a codespace interactively:

```bash
gh codespace delete
```

- Display help for a subcommand:

```bash
gh codespace subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-codespace: add page (#7239) | 2021-11-03T17:08:29 | [d9157ae2cc2e](https://github.com/tldr-pages/tldr/commit/d9157ae2cc2ecba8a4bb0bbfcb28a2f0476f8f5d)

