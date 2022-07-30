---
author: ['André Bação', 'lucas schneider', 'Seth Falco']
date: 1656325392
title: "gopass"
description: "gopass, Standard Unix Password Manager for Teams. Written in Go."
categories: "common"
---
> More information: <https://www.gopass.pw>.

- Initialize the configuration settings:

```bash
gopass init
```

- Create a new entry:

```bash
gopass new
```

- Show all stores:

```bash
gopass mounts
```

- Mount a shared Git store:

```bash
gopass mounts add store_name git_repo_url
```

- Search interactively using a keyword:

```bash
gopass show keyword
```

- Search using a keyword:

```bash
gopass find keyword
```

- Sync all mounted stores:

```bash
gopass sync
```

- Show a particular password entry:

```bash
gopass store_name|path/to/directory|email@email.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[André Bação](mailto:andre@bacao.pt) | gopass: move to common (#3640) | 2019-12-05T20:56:59 | [ef19080c95fe](https://github.com/tldr-pages/tldr/commit/ef19080c95fe759de0daf52e29423e513487e819)

