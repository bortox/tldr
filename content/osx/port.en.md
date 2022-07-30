---
author: ['pixel', 'personalnadir', 'Seth Falco']
date: 1644810209
title: "port"
description: "port, Package manager for macOS."
categories: "osx"
---
> More information: <https://www.macports.org>.

- Search for a package:

```bash
port search search_term
```

- Install a package:

```bash
sudo port install package_name
```

- List installed packages:

```bash
port installed
```

- Update port and fetch the latest list of available packages:

```bash
sudo port selfupdate
```

- Upgrade outdated packages:

```bash
sudo port upgrade outdated
```

- Remove old versions of installed packages:

```bash
sudo port uninstall inactive
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | networksetup, port, xcode-select, xcodebuild: add more information links (#7754) * port: more info * xcodebuild: more info * xcode- [...] | 2022-02-14T04:43:29 | [4e2c525e311a](https://github.com/tldr-pages/tldr/commit/4e2c525e311a327155c32b467b5ff24b8df22318)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[personalnadir](mailto:personalnadir@gmail.com) | port: improve readability Changed text for uninstall inactive | 2017-10-06T10:11:50 | [522f77851962](https://github.com/tldr-pages/tldr/commit/522f77851962cd3600213ecdc2768c8fb2142736)
[personalnadir](mailto:personalnadir@gmail.com) | port.md: fix typo Also improved selfupdate command description | 2017-09-20T12:02:57 | [6ef60676d08b](https://github.com/tldr-pages/tldr/commit/6ef60676d08bf8dfd6fb2f56e42c370429104558)
[personalnadir](mailto:personalnadir@gmail.com) | port.md: fix typo | 2017-09-19T13:26:17 | [f427ccd46041](https://github.com/tldr-pages/tldr/commit/f427ccd46041db4156c3b4141755526a032bc61c)
[personalnadir](mailto:personalnadir@gmail.com) | Create port.md Proposed page for mac ports port cli. | 2017-09-19T13:17:27 | [9b5cd5d4fb94](https://github.com/tldr-pages/tldr/commit/9b5cd5d4fb9400cee48059147a7ad476f91d6ca4)

