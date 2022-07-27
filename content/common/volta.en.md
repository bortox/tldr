---
author: ['Nicolas Kosinski']
date: 1639652883
title: "volta, TLDR Pages"
description: "volta, A JavaScript Tool Manager that installs Node.js runtimes, npm and Yarn package managers, or any binaries from npm."
categories: "common"
---
> More information: <https://volta.sh>.

- List all installed tools:

```bash
volta list
```

- Install the latest version of a tool:

```bash
volta install node|npm|yarn|package_name
```

- Install a specific version of a tool:

```bash
volta install node|npm|yarn@version
```

- Choose a tool version for a project (will store it in `package.json`):

```bash
volta pin node|npm|yarn@version
```

- Display help:

```bash
volta help
```

- Display help for a subcommand:

```bash
volta help fetch|install|uninstall|pin|list|completions|which|setup|run|help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@users.noreply.github.com) | volta: add page (#7515) | 2021-12-16T12:08:03 | [6cfa99a08f90](https://github.com/tldr-pages/tldr/commit/6cfa99a08f9000a1b7dbe8a8f49c6d521a2b1640)

