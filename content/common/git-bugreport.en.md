---
author: ['bl-ue', 'Seth Falco']
date: 1629050349
title: "git bugreport"
description: "git bugreport, Captures debug information from the system and user, generating a text file to aid in the reporting of a bug in Git."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-bugreport>.

- Create a new bug report file in the current directory:

```bash
git bugreport
```

- Create a new bug report file in the specified directory, creating it if it does not exist:

```bash
git bugreport --output-directory path/to/directory
```

- Create a new bug report file with the specified filename suffix in `strftime` format:

```bash
git bugreport --suffix %m%d%y
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-bugreport: add more information link (#5543) | 2021-03-29T23:48:15 | [4d76ad0fe2fa](https://github.com/tldr-pages/tldr/commit/4d76ad0fe2fab53f3f81d645ab6c4e7482eaf966)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-bugreport: add page (#5097) | 2021-01-08T08:36:54 | [4ebca809112b](https://github.com/tldr-pages/tldr/commit/4ebca809112b8160824512e0ff0978a15b8a0b9a)

