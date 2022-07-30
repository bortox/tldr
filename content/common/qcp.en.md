---
author: ['Waldir Pimenta', 'Nattawut Phetmak']
date: 1577816877
title: "qcp"
description: "qcp, Copy files using the default text editor to define the filenames."
categories: "common"
---
> More information: <https://www.nongnu.org/renameutils/>.

- Copy a single file (open an editor with the source filename on the left and the target filename on the right):

```bash
qcp source_file
```

- Copy multiple JPG files:

```bash
qcp *.jpg
```

- Copy files, but swap the positions of the source and the target filenames in the editor:

```bash
qcp --option swap *.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Waldir Pimenta](mailto:waldyrious@gmail.com) | qcp, qmv: small tweaks (#3712) | 2019-12-31T19:27:57 | [bb392b5654d1](https://github.com/tldr-pages/tldr/commit/bb392b5654d1c030a770807cbf5ec8ebfb0bb435)
[Nattawut Phetmak](mailto:neizod@gmail.com) | qmv, qcp: add page (#3458) | 2019-11-05T08:33:21 | [64494a2f6a76](https://github.com/tldr-pages/tldr/commit/64494a2f6a7665da5cc5cbd89e584a39938dabe6)

