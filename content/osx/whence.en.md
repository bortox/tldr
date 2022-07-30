---
author: ['Daniel Bayley', 'Emily Grace Seville']
date: 1644837703
title: "whence"
description: "whence, A zsh builtin to indicate how a given command would be interpreted."
categories: "osx"
---
> More information: <https://www.unix.com/man-page/OpenSolaris/1/whence/>.

- Interpret {{command}}, with expansion if defined as an `alias` (similar to the `command -v` builtin):

```bash
whence "command"
```

- Display type of {{command}}, with location if defined as a function, or binary (equivalent to the `type` and `command -V` builtins):

```bash
whence -v "command"
```

- Same as above, except display content of shell functions instead of location (equivalent to `which` builtin):

```bash
whence -c "command"
```

- Same as above, but show all occurrences on command path (equivalent to the `where` builtin):

```bash
whence -ca "command"
```

- Search only the `PATH` for {{command}}, ignoring builtins, aliases or shell functions (equivalent to the `where` command):

```bash
whence -p "command"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Daniel Bayley](mailto:daniel.bayley@me.com) | whence: add page (#4021) | 2020-05-14T17:04:48 | [5ddf587e3ae8](https://github.com/tldr-pages/tldr/commit/5ddf587e3ae8e507c707e70ba4e1904e766ef89b)

