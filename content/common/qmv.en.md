---
author: ['Waldir Pimenta', 'Nattawut Phetmak']
date: 1577816877
title: "qmv"
description: "qmv, Move files and directories using the default text editor to define the filenames."
categories: "common"
---
> More information: <https://www.nongnu.org/renameutils/>.

- Move a single file (open an editor with the source filename on the left and the target filename on the right):

```bash
qmv source_file
```

- Move multiple JPG files:

```bash
qmv *.jpg
```

- Move multiple directories:

```bash
qmv -d path/to/directory1 path/to/directory2 path/to/directory3
```

- Move all files and directories inside a directory:

```bash
qmv --recursive path/to/directory
```

- Move files, but swap the positions of the source and the target filenames in the editor:

```bash
qmv --option swap *.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Waldir Pimenta](mailto:waldyrious@gmail.com) | qcp, qmv: small tweaks (#3712) | 2019-12-31T19:27:57 | [bb392b5654d1](https://github.com/tldr-pages/tldr/commit/bb392b5654d1c030a770807cbf5ec8ebfb0bb435)
[Nattawut Phetmak](mailto:neizod@gmail.com) | qmv, qcp: add page (#3458) | 2019-11-05T08:33:21 | [64494a2f6a76](https://github.com/tldr-pages/tldr/commit/64494a2f6a7665da5cc5cbd89e584a39938dabe6)

