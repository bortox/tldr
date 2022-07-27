---
author: ['Ruben Vereecken', 'kuanyui', 'Victorhck', 'Seth Falco']
date: 1629050349
title: "zypper, TLDR Pages"
description: "zypper, SUSE & openSUSE package management utility."
categories: "linux"
---
> More information: <https://en.opensuse.org/SDB:Zypper_manual>.

- Synchronize list of packages and versions available:

```bash
zypper refresh
```

- Install a new package:

```bash
zypper install package
```

- Remove a package:

```bash
zypper remove package
```

- Upgrade installed packages to the newest available versions:

```bash
zypper update
```

- Search package via keyword:

```bash
zypper search keyword
```

- Show information related to configured repositories:

```bash
zypper repos --sort-by-priority
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Victorhck](mailto:victorhck@mailbox.org) | zypper: add link and example about repos management (#6225) | 2021-07-14T21:23:26 | [5c5004175521](https://github.com/tldr-pages/tldr/commit/5c500417552118fa4d70c2cfc9f6c219b4156951)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[kuanyui](mailto:azazabc123@gmail.com) | Capitalize first character. | 2016-01-05T08:24:50 | [3fb81447ca12](https://github.com/tldr-pages/tldr/commit/3fb81447ca12bc903bab0d1f45ae275700a3c7c3)
[kuanyui](mailto:azazabc123@gmail.com) | Add linux/zypper | 2016-01-04T19:32:04 | [a46d450306cc](https://github.com/tldr-pages/tldr/commit/a46d450306cc4a5d1c37fd548bb5ce8383fc9d79)

