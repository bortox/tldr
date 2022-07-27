---
author: ['bl-ue', 'Ian Oxborrow 3', 'Emily Grace Seville']
date: 1644837703
title: "softwareupdate, TLDR Pages"
description: "softwareupdate, A tool for updating macOS App Store apps via the command-line."
categories: "osx"
---
> More information: <https://ss64.com/osx/softwareupdate.html>.

- List all available updates:

```bash
softwareupdate --list
```

- Download and install all updates:

```bash
softwareupdate --install --all
```

- Download and install all recommended updates:

```bash
softwareupdate --install --req
```

- Download and install a specific app:

```bash
softwareupdate --install update_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Ian Oxborrow 3](mailto:ian.s.oxborrow@gmail.com) | softwareupdate: add page (#1573) | 2017-10-28T20:25:57 | [713a0d0c39c5](https://github.com/tldr-pages/tldr/commit/713a0d0c39c5f8cf761dbd171dac4f8b5ffda672)

