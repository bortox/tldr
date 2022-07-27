---
author: ['Puneetha Pai']
date: 1598050405
title: "dvc config, TLDR Pages"
description: "dvc config, Low level command to manage custom configuration options for dvc repositories."
categories: "common"
---
> These configurations can be on project, local, global, or system level.

> More information: <https://dvc.org/doc/command-reference/config>.

- Get the name of the default remote:

```bash
dvc config core.remote
```

- Set the project's default remote:

```bash
dvc config core.remote remote_name
```

- Unset the project's default remote:

```bash
dvc config --unset core.remote
```

- Get the config value for a specified key for the current project:

```bash
dvc config key
```

- Set the config value for a key on a project level:

```bash
dvc config key value
```

- Unset a project level config value for a given key:

```bash
dvc config --unset key
```

- Set a local, global, or system level config value:

```bash
dvc config --local/global/system key value
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Puneetha Pai](mailto:21996583+PuneethaPai@users.noreply.github.com) | Apply suggestions from code review Thanks @sbrl. Will keep grammatical mistakes to minimum next time :smile Co-authored-by: [...] | 2020-08-22T00:53:25 | [91e565ba811e](https://github.com/tldr-pages/tldr/commit/91e565ba811e1112dc3e96f46d4b3d2bd96095c2)
[Puneetha Pai](mailto:puneethapai29@gmail.com) | DVC: add pages for sub commands commit, config, dag | 2020-08-22T00:53:25 | [e94e07d26dc2](https://github.com/tldr-pages/tldr/commit/e94e07d26dc270c7a38086a7c69239ecdf1f97f7)

