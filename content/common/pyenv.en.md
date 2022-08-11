---
author: ['周丰', 'Lucas Gabriel Schneider', 'Balázs Úr', 'pxgamer', 'Muhammad Falak R Wani']
date: 1660129032
title: "pyenv"
description: "pyenv, Switch between multiple versions of Python easily."
categories: "common"
---
> More information: <https://github.com/pyenv/pyenv>.

- List all available commands:

```bash
pyenv commands
```

- List all Python versions under the `${PYENV_ROOT}/versions` directory:

```bash
pyenv versions
```

- List all Python versions that can be installed from upstream:

```bash
pyenv install --list
```

- Install a Python version under the `${PYENV_ROOT}/versions` directory:

```bash
pyenv install 2.7.10
```

- Uninstall a Python version under the `${PYENV_ROOT}/versions` directory:

```bash
pyenv uninstall 2.7.10
```

- Set Python version to be used globally in the current machine:

```bash
pyenv global 2.7.10
```

- Set Python version to be used in the current directory and all directories below it:

```bash
pyenv local 2.7.10
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | pyenv: add example to list all installable versions (#8327) * pyenv: add example to list all installable versions * pyenv: add italian [...] | 2022-08-10T12:57:12 | [86c27744b0ba](https://github.com/tldr-pages/tldr/commit/86c27744b0baa0b222363aac1905de269052d05b)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[pxgamer](mailto:owzie123@gmail.com) | pyenv: add link to homepage | 2019-05-31T20:47:40 | [9cd7b4a31616](https://github.com/tldr-pages/tldr/commit/9cd7b4a316168be87da30adde535c489aea80a1d)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: remove superfluous white spaces (#2801) | 2019-02-24T16:47:41 | [ad3772d8cbd5](https://github.com/tldr-pages/tldr/commit/ad3772d8cbd5a61fecfb38ab13bdc7b104b4ecdf)
[周丰](mailto:zhoufengloop@gmail.com) | pyenv: add page (#995) | 2016-08-09T09:38:21 | [7da70b4f3136](https://github.com/tldr-pages/tldr/commit/7da70b4f313611299f6d09037f74dd8e87e12d48)

