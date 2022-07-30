---
author: ['Fabio Kleis']
date: 1633358809
title: "pacstall"
description: "pacstall, An AUR package manager for Ubuntu."
categories: "linux"
---
> More information: <https://github.com/pacstall/pacstall>.

- Search the package database for a package name:

```bash
pacstall --search package_name
```

- Install a package:

```bash
pacstall --install package_name
```

- Remove a package:

```bash
pacstall --remove package_name
```

- Add a repository to the database (only GitHub and GitLab are supported):

```bash
pacstall --add-repo remote_repository_location
```

- Update pacstall's scripts:

```bash
pacstall --update
```

- Update all packages:

```bash
pacstall --upgrade
```

- Display information about a package:

```bash
pacstall --query-info package_name
```

- List all installed packages:

```bash
pacstall --list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Fabio Kleis](mailto:66813406+Fabiokleis@users.noreply.github.com) | pacstall: add page (#6732) | 2021-10-04T16:46:49 | [0b5aa3373684](https://github.com/tldr-pages/tldr/commit/0b5aa3373684dbbe4df8eacd5073fbf2a9506986)

