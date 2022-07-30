---
author: ['Timothy Hopper', 'pxgamer', 'Lucas Gabriel Schneider', 'Marco Bonelli']
date: 1612112718
title: "tox"
description: "tox, Automate Python testing across multiple Python versions."
categories: "common"
---
> Use tox.ini to configure environments and test command.

> More information: <https://github.com/tox-dev/tox>.

- Run tests on all test environments:

```bash
tox
```

- Create a `tox.ini` configuration:

```bash
tox-quickstart
```

- List the available environments:

```bash
tox --listenvs-all
```

- Run tests on a specific environment (e.g. python 3.6):

```bash
tox -e py36
```

- Force the virtual environment to be recreated:

```bash
tox --recreate -e py27
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | tox: add link to homepage | 2019-05-14T19:58:59 | [265ee790606b](https://github.com/tldr-pages/tldr/commit/265ee790606b8dfbac8ca676a097b3197aff473e)
[Timothy Hopper](mailto:tdhopper@users.noreply.github.com) | tox: add page (#2225) | 2018-07-29T00:19:14 | [f8d410629d93](https://github.com/tldr-pages/tldr/commit/f8d410629d93c8930c7e875e46f111afc5558798)

