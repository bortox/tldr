---
author: ['Michael Spear', 'Starbeamrainbowlabs', 'Marco Bonelli', 'David Heimann', 'Ivor Benderavage']
date: 1604236293
title: "pipenv"
description: "pipenv, Simple and unified Python development workflow."
categories: "common"
---
> Manages packages and the virtual environment for a project.

> More information: <https://pypi.org/project/pipenv>.

- Create a new project:

```bash
pipenv
```

- Create a new project using Python 3:

```bash
pipenv --three
```

- Install a package:

```bash
pipenv install package_name
```

- Install all the dependencies for a project:

```bash
pipenv install
```

- Install all the dependencies for a project (including dev packages):

```bash
pipenv install --dev
```

- Uninstall a package:

```bash
pipenv uninstall package_name
```

- Start a shell within the created virtual environment:

```bash
pipenv shell
```

- Generate a `requirements.txt` (list of dependencies) for a project:

```bash
pipenv lock --requirements
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | pipenv: add example for not dev packages (#4880) | 2020-11-01T14:11:33 | [e009d7ceba4a](https://github.com/tldr-pages/tldr/commit/e009d7ceba4a21a7920c47f78f4f2d2bf6810854)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: fix syntax | 2019-02-03T01:28:36 | [334c0b4fa3ea](https://github.com/tldr-pages/tldr/commit/334c0b4fa3ea6f24c50d62061db9075125cc608b)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | pipenv: add homepage | 2019-02-03T01:28:36 | [95d650777977](https://github.com/tldr-pages/tldr/commit/95d6507779771d429a1123a952859d6141d6c698)
[Michael Spear](mailto:mwspear@gmail.com) | pipenv: add lock command with --requirements flag | 2018-08-20T19:01:40 | [bedb6b459f6a](https://github.com/tldr-pages/tldr/commit/bedb6b459f6a7d14dfa5a10990d233766d305b9c)
[David Heimann](mailto:heimann@users.noreply.github.com) | pipenv: add page (#1791) | 2017-12-15T04:20:25 | [93c8c59f8c13](https://github.com/tldr-pages/tldr/commit/93c8c59f8c13892403b488c1bad47d8d96819e58)

