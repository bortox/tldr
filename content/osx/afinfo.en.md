---
author: ['Seth Falco', 'Gary Li', 'Kyle', 'Emily Grace Seville']
date: 1644837703
title: "afinfo, TLDR Pages"
description: "afinfo, Audio file metadata parser for OS X."
categories: "osx"
---
> Built-in command of OS X.

> More information: <https://ss64.com/osx/afinfo.html>.

- Display info of a given audio file:

```bash
afinfo path/to/file
```

- Print a one line description of the audio file:

```bash
afinfo --brief path/to/file
```

- Print metadata info and contents of the audio file's InfoDictionary:

```bash
afinfo --info path/to/file
```

- Print output in XML format:

```bash
afinfo --xml path/to/file
```

- Print warnings for the audio file if any:

```bash
afinfo --warnings path/to/file
```

- Display help for full usage:

```bash
afinfo --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Gary Li](mailto:15998246+garily@users.noreply.github.com) | afinfo: add page (en, zh) (#3652) | 2019-12-10T11:29:33 | [8df38c39895c](https://github.com/tldr-pages/tldr/commit/8df38c39895ce6c6bf6e1b112568083adb14ea61)

