---
author: ['Axel Navarro']
date: 1633335763
title: "nvram"
description: "nvram, Manipulate firmware variables."
categories: "osx"
---
> More information: <https://ss64.com/osx/nvram.html>.

- [p]rint all the variables stored in the NVRAM:

```bash
nvram -p
```

- [p]rint all the variables stored in the NVRAM using [x]ML format:

```bash
nvram -xp
```

- Modify the value of a firmware variable:

```bash
sudo nvram name="value"
```

- [d]elete a firmware variable:

```bash
sudo nvram -d name
```

- [c]lear all the firmware variables:

```bash
sudo nvram -c
```

- Set a firmware variable from a specific [x]ML [f]ile:

```bash
sudo nvram -xf path/to/file.xml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | nvram: add page (#6617) | 2021-10-04T10:22:43 | [ff7516b063f7](https://github.com/tldr-pages/tldr/commit/ff7516b063f7ddaef1194b5a737fdde0bfcf1c4e)

