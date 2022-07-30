---
author: ['adrian5', 'Robert Barat', 'Seth Falco']
date: 1623981137
title: "pip3"
description: "pip3, Python package manager."
categories: "common"
---
> More information: <https://pip.pypa.io>.

- Find available packages:

```bash
pip3 search package_name
```

- Install a package:

```bash
pip3 install package_name
```

- Install a specific version of a package:

```bash
pip3 install package_name==package_version
```

- Upgrade a package:

```bash
pip3 install --upgrade package_name
```

- Uninstall a package:

```bash
pip3 uninstall package_name
```

- Save the list of installed packages to a file:

```bash
pip3 freeze > requirements.txt
```

- Install packages from a file:

```bash
pip3 install --requirement requirements.txt
```

- Show installed package info:

```bash
pip3 show package_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | pip3: fix argument spelling (#6140) | 2021-06-18T03:52:17 | [f50ae7e90575](https://github.com/tldr-pages/tldr/commit/f50ae7e90575c96caf4175bf38497df2edce06d3)
[adrian5](mailto:adrian5@users.noreply.github.com) | pip3: add search command | 2019-10-23T05:41:41 | [22ad2cbc3df0](https://github.com/tldr-pages/tldr/commit/22ad2cbc3df0cf53449dd64c1d522b96902b4101)
[Robert Barat](mailto:volt4ire@users.noreply.github.com) | pip3: add page (#3210) | 2019-07-31T05:16:47 | [ab444b897214](https://github.com/tldr-pages/tldr/commit/ab444b8972145914270fa650c98ad5dadf3fad58)

