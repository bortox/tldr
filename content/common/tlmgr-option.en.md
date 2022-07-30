---
author: ['marchersimon']
date: 1634486977
title: "tlmgr option"
description: "tlmgr option, TeX Live settings manager."
categories: "common"
---
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- List all TeX Live settings:

```bash
tlmgr option showall
```

- List all currently set Tex Live settings:

```bash
tlmgr option show
```

- Print all TeX Live settings in JSON format:

```bash
tlmgr option showall --json
```

- Show the value of a specific TeX Live setting:

```bash
tlmgr option setting
```

- Modify the value of a specific TeX Live setting:

```bash
tlmgr option setting value
```

- Set TeX Live to get future updates from the internet after installing from DVD:

```bash
tlmgr option repository https://mirror.ctan.org/systems/texlive/tlnet
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tlmgr-option: add page (#6576) | 2021-10-17T18:09:37 | [4d8a5b4dab50](https://github.com/tldr-pages/tldr/commit/4d8a5b4dab50b791e3f0f1af33444a62d999b889)

