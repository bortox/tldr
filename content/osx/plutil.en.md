---
author: ['Matthew Flint', 'Lucas Gabriel Schneider', 'Emily Grace Seville']
date: 1644837703
title: "plutil"
description: "plutil, View, convert, validate, or edit property list ('plist') files."
categories: "osx"
---
> More information: <https://www.manpagez.com/man/1/plutil/>.

- Display the contents of one or more plist files in human-readable format:

```bash
plutil -p file1.plist file2.plist ...
```

- Convert one or more plist files to XML format, overwriting the original files in-place:

```bash
plutil -convert xml1 file1.plist file2.plist ...
```

- Convert one or more plist files to binary format, overwriting the original files in-place:

```bash
plutil -convert binary1 file1.plist file2.plist ...
```

- Convert a plist file to a different format, writing to a new file:

```bash
plutil -convert xml1|binary1|json|swift|objc path/to/file.plist -o path/to/new_file.plist
```

- Convert a plist file to a different format, writing to stdout:

```bash
plutil -convert xml1|binary1|json|swift|objc path/to/file.plist -o -
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Matthew Flint](mailto:355086+mflint@users.noreply.github.com) | plutil: add page (#4343) | 2020-09-16T15:40:03 | [aec11c1aafc5](https://github.com/tldr-pages/tldr/commit/aec11c1aafc5db9f7f2b1347defb6638c8790001)

