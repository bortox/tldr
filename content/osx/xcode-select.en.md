---
author: ['pixel', 'Tanner Bennett', 'Emily Grace Seville']
date: 1644837703
title: "xcode-select, TLDR Pages"
description: "xcode-select, Switch between different versions of Xcode and the included developer tools."
categories: "osx"
---
> Also used to update the path to Xcode if it is moved after installation.

> More information: <https://developer.apple.com/library/archive/technotes/tn2339/_index.html>.

- Install Xcode's command-line tools:

```bash
xcode-select --install
```

- Select a given path as the active developer directory:

```bash
xcode-select --switch path/to/Xcode.app/Contents/Developer
```

- Select a given Xcode instance and use its developer directory as the active one:

```bash
xcode-select --switch path/to/Xcode.app
```

- Print the currently selected developer directory:

```bash
xcode-select --print-path
```

- Discard any user-specified developer directory so that it will be found via the default search mechanism:

```bash
sudo xcode-select --reset
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[pixel](mailto:chrissx@chrissx.de) | networksetup, port, xcode-select, xcodebuild: add more information links (#7754) * port: more info * xcodebuild: more info * xcode- [...] | 2022-02-14T04:43:29 | [4e2c525e311a](https://github.com/tldr-pages/tldr/commit/4e2c525e311a327155c32b467b5ff24b8df22318)
[Tanner Bennett](mailto:tannerbennett@me.com) | xcode-select: add page (#3826) Co-Authored-By: Owen Voke <owzie123@gmail.com> Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-02-05T16:58:42 | [9c86eafbc87e](https://github.com/tldr-pages/tldr/commit/9c86eafbc87ed8779b2bbe71ed64ccb60eab0bfa)

