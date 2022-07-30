---
author: ['Sarah Li']
date: 1572372128
title: "hlint"
description: "hlint, Tool for suggesting improvements to Haskell code."
categories: "linux"
---
> More information: <http://hackage.haskell.org/package/hlint>.

- Display suggestions for a given file:

```bash
hlint path/to/file options
```

- Check all Haskell files and generate a report:

```bash
hlint path/to/directory --report
```

- Automatically apply most suggestions:

```bash
hlint path/to/file --refactor
```

- Display additional options:

```bash
hlint path/to/file --refactor-options
```

- Generate a settings file ignoring all outstanding hints:

```bash
hlint path/to/file --default > .hlint.yaml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sarah Li](mailto:43288700+sarahliii@users.noreply.github.com) | hlint: add page (#3480) | 2019-10-29T19:02:08 | [338541de6fb9](https://github.com/tldr-pages/tldr/commit/338541de6fb974cb11d8a3fdf44ab82525d93358)

