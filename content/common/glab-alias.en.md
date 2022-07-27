---
author: ['Reinhart Previano Koentjoro']
date: 1651488938
title: "glab alias, TLDR Pages"
description: "glab alias, Manage GitLab CLI command aliases from the command-line."
categories: "common"
---
> More information: <https://glab.readthedocs.io/en/latest/alias>.

- Display the subcommand help:

```bash
glab alias
```

- List all the aliases `glab` is configured to use:

```bash
glab alias list
```

- Create a `glab` subcommand alias:

```bash
glab alias set mrv 'mr view'
```

- Set a shell command as a `glab` subcommand:

```bash
glab alias set --shell alias_name command
```

- Delete a command shortcut:

```bash
glab alias delete alias_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | gh*, glab*: standardize documentation (#7957) | 2022-05-02T12:55:38 | [6ed9681dbcd6](https://github.com/tldr-pages/tldr/commit/6ed9681dbcd680e9529c8238221f7fab9cd2c130)
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | glab-alias: add page (#7641) | 2022-01-14T14:33:08 | [bdbd53c5ee4f](https://github.com/tldr-pages/tldr/commit/bdbd53c5ee4fabc2fdacb4e272cb6967ee9be7d9)

