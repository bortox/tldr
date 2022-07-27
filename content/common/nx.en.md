---
author: ['Locour']
date: 1636310923
title: "nx, TLDR Pages"
description: "nx, CLI utility for managing `nx` workspaces."
categories: "common"
---
> More information: <https://nx.dev/l/r/getting-started/nx-cli>.

- Build a specific project:

```bash
nx build project
```

- Test a specific project:

```bash
nx test project
```

- Execute a target on a specific project:

```bash
nx run project:target
```

- Execute a target on multiple projects:

```bash
nx run-many --target target --projects project1,project2
```

- Execute a target on all projects in the workspace:

```bash
nx run-many --target target --all
```

- Execute a target only on projects that have been changed:

```bash
nx affected --target target
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Locour](mailto:Locour@users.noreply.github.com) | nx: add page (#7224) | 2021-11-07T19:48:43 | [9f8edc9891cc](https://github.com/tldr-pages/tldr/commit/9f8edc9891ccc5f8d828a57d0efbe5c1bdde1d07)

