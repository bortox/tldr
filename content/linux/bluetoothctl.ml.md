---
author: ['CleanMachine1', 'Axel Navarro']
date: 1643827401
title: "bluetoothctl, TLDR Pages"
description: "bluetoothctl, കമാൻഡ് ലൈനിൽ നിന്ന് ബ്ലൂടൂത്ത് ഉപകരണങ്ങൾ മാനേജുചെയ്യുക."
categories: "linux"
---
> കൂടുതൽ വിവരങ്ങൾ: <https://bitbucket.org/serkanp/bluetoothctl>.

- ബ്ലൂടൂത്ത്സിറ്റിഎൽ ഷെല്ലിൽ കേറാൻ:

```bash
bluetoothctl
```

- ഉപകരണങ്ങളുടെ പട്ടിക കാണാൻ:

```bash
bluetoothctl --devices
```

- ഒരു ഉപകരണം ജോടിയാക്കുക:

```bash
bluetoothctl --pair മാക്_വിലാസം
```

- ഒരു ഉപകരണം നീക്കംചെയ്യുക:

```bash
bluetoothctl --remove മാക്_വിലാസം
```

- ജോഡിയായ ഉപകരണവുമായി ബന്ധിപ്പിക്കുക:

```bash
bluetoothctl --connect മാക്_വിലാസം
```

- ഒരു ജോഡിയായ ഉപകരണവുമായുള്ള ബന്ധം വിച്ഛേദിക്കുക:

```bash
bluetoothctl --disconnect മാക്_വിലാസം
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | *: use author link instead of npm package (#7730) | 2022-02-02T19:43:21 | [c2c16f61acbd](https://github.com/tldr-pages/tldr/commit/c2c16f61acbdca1933961fbbc20a80bdae76ece5)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | bluetooth: move to correct directory (#7296) Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-10-31T02:12:17 | [75141f0fffbc](https://github.com/tldr-pages/tldr/commit/75141f0fffbc8aaff38c94540f38a26961946a4d)

