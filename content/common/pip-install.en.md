---
author: ['Dhruva Kashyap', 'Dominik Geldmacher', 'Azat Akhmetov']
date: 1634266838
title: "pip install"
description: "pip install, Install Python packages."
categories: "common"
---
> More information: <https://pip.pypa.io>.

- Install a package:

```bash
pip install package_name
```

- Install a specific version of a package:

```bash
pip install package_name==package_version
```

- Install packages listed in a file:

```bash
pip install --requirement path/to/requirements.txt
```

- Install packages from an URL or local file archive (.tar.gz | .whl):

```bash
pip install --find-links url|path/to/file
```

- Install the local package in the current directory in develop (editable) mode:

```bash
pip install --editable .
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dhruva Kashyap](mailto:40919082+DhruvaKashyap@users.noreply.github.com) | pip-install, pip-uninstall: add page and refresh (#7003) | 2021-10-15T05:00:38 | [748db138037a](https://github.com/tldr-pages/tldr/commit/748db138037a213b78ca18bf1d85a79290e0addc)
[Dominik Geldmacher](mailto:oryon@cyberise.de) | pip-install: add --find-links example (#6319) | 2021-09-01T19:22:20 | [60862471314f](https://github.com/tldr-pages/tldr/commit/60862471314f9ae20af8f1b4114abc3215c4cbd6)
[Azat Akhmetov](mailto:51468504+metov@users.noreply.github.com) | pip-install: add page (#4983) | 2020-12-30T14:25:03 | [97bfd149cf83](https://github.com/tldr-pages/tldr/commit/97bfd149cf833045b97331f4258fae93c2f2f175)

