---
author: ['Silas Benson', 'Hugh Wimberly', 'Lucas Gabriel Schneider']
date: 1638281531
title: "poetry, TLDR Pages"
description: "poetry, Manage Python packages and dependencies."
categories: "common"
---
> More information: <https://python-poetry.org/docs>.

- Create a new Poetry project in the directory with a specific name:

```bash
poetry new project_name
```

- Install a dependency and its subdependencies:

```bash
poetry add dependency
```

- Install a development dependency and its subdependencies:

```bash
poetry add --dev dependency
```

- Interactively initialize the current directory as a new Poetry project:

```bash
poetry init
```

- Get the latest version of all dependencies and update `poetry.lock`:

```bash
poetry update
```

- Execute a command inside the project's virtual environment:

```bash
poetry run command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Silas Benson](mailto:silasvb@gmail.com) | poetry: add `add --dev` example (#7497) | 2021-11-30T15:12:11 | [9bc80d1d42a8](https://github.com/tldr-pages/tldr/commit/9bc80d1d42a80a05806ec4285446768b125b194d)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Hugh Wimberly](mailto:hugh.wimberly@gmail.com) | poetry: add page (#3832) * poetry: add page * Add period for command description. * Describe action rather than use a token Co- [...] | 2020-02-03T17:46:41 | [a3ccc785e811](https://github.com/tldr-pages/tldr/commit/a3ccc785e811c6e651ac013251deb8b2950a9c7e)

