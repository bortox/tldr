---
author: ['Philipp Moers']
date: 1658965490
title: "picom-trans"
description: "picom-trans, Set the window opacity for the `picom` window compositor."
categories: "common"
---
> More information: <https://github.com/yshui/picom>.

- Set the currently focused window opacity to a specific percentage:

```bash
picom-trans --current --opacity 90
```

- Set the opacity of a window with a specific name:

```bash
picom-trans --name Firefox --opacity 90
```

- Set the opacity of a specific window selected via mouse cursor:

```bash
picom-trans --select --opacity 90
```

- Toggle the opacity of a specific window:

```bash
picom-trans --name Firefox --toggle
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Philipp Moers](mailto:soziflip+github@gmail.com) | picom-trans: add page (#8244) | 2022-07-28T01:44:50 | [b0c73a81b9f1](https://github.com/tldr-pages/tldr/commit/b0c73a81b9f1071aa545cfcec0a58d50a0658ba6)

