---
author: ['Aitzaz Mumtaz Khan']
date: 1588334184
title: "virtualenvwrapper, TLDR Pages"
description: "virtualenvwrapper, Group of simple wrapper commands for Python's `virtualenv` tool."
categories: "common"
---
> More information: <http://virtualenvwrapper.readthedocs.org>.

- Create a new Python `virtualenv` in `$WORKON_HOME`:

```bash
mkvirtualenv virtualenv_name
```

- Create a `virtualenv` for a specific Python version:

```bash
mkvirtualenv --python /usr/local/bin/python3.8 virtualenv_name
```

- Activate or use a different `virtualenv`:

```bash
workon virtualenv_name
```

- Stop the `virtualenv`:

```bash
deactivate
```

- List all virtual environments:

```bash
lsvirtualenv
```

- Remove a `virtualenv`:

```bash
rmvirtualenv virtualenv_name
```

- Get summary of all virtualenvwrapper commands:

```bash
virtualenvwrapper
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Aitzaz Mumtaz Khan](mailto:aitzaz.mumtaz@arbisoft.com) | virtualenvwrapper: add page (#4010) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-05-01T13:56:24 | [f93d709f6143](https://github.com/tldr-pages/tldr/commit/f93d709f61432a068fee6048f24c369af8af121f)

