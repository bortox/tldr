---
author: ['xphade', 'CleanMachine1', 'fejx']
date: 1656619119
title: "unix2mac, TLDR Pages"
description: "unix2mac, Change Unix-style line endings to macOS-style."
categories: "linux"
---
> Replaces LF with CR.

> More information: <https://waterlan.home.xs4all.nl/dos2unix.html>.

- Change the line endings of a file:

```bash
unix2mac filename
```

- Create a copy with macOS-style line endings:

```bash
unix2mac -n filename new_filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[xphade](mailto:18196286+xphade@users.noreply.github.com) | dos2unix, mac2unix, unix2dos, unix2mac: fix error in descriptions (#8082) | 2022-06-30T21:58:39 | [ba5ce3932331](https://github.com/tldr-pages/tldr/commit/ba5ce393233134279bd4386feac891af500edfe8)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | linux/u*: add links (#6190) | 2021-07-11T19:17:29 | [3ac60f1062ba](https://github.com/tldr-pages/tldr/commit/3ac60f1062ba714b493cee9c4e413901867c9f93)
[fejx](mailto:fejx@users.noreply.github.com) | dos2unix, unix2dos, mac2unix, unix2mac: rephrase wording in first example Adding 'the' is more accurate because it's *all* of the line [...] | 2020-05-13T01:52:23 | [2522bce7c2f3](https://github.com/tldr-pages/tldr/commit/2522bce7c2f394f490a3fad2637c539f0e0f4d93)
[fejx](mailto:fejx@users.noreply.github.com) | dos2unix, unix2dos, mac2unix, unix2mac: use consistent naming Apply suggestions from code review Co-authored-by: Zlatan Vasović [...] | 2020-05-13T01:52:23 | [cf1b9177b7ea](https://github.com/tldr-pages/tldr/commit/cf1b9177b7ea00dfa98fa377e2d2d4c65c27fef3)
[fejx](mailto:fejx@users.noreply.github.com) | unix2mac: add page | 2020-05-13T01:52:23 | [73969022679d](https://github.com/tldr-pages/tldr/commit/73969022679d19aa388ca757797f8af8c7a375f5)

