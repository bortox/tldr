---
author: ['Daniel Bayley', 'Igor Shubovych', 'Emily Grace Seville', 'Thomas Wünsche', 'sfarzy', 'Leandro Ostera']
date: 1644837703
title: "defaults"
description: "defaults, Read and write macOS user configuration for applications."
categories: "osx"
---
> More information: <https://ss64.com/osx/defaults.html>.

- Read system defaults for an application option:

```bash
defaults read "application" "option"
```

- Read default values for an application option:

```bash
defaults read -app "application" "option"
```

- Search for a keyword in domain names, keys, and values:

```bash
defaults find "keyword"
```

- Write the default value of an application option:

```bash
defaults write "application" "option" -type value
```

- Speed up Mission Control animations:

```bash
defaults write com.apple.Dock expose-animation-duration -float 0.1
```

- Delete all defaults of an application:

```bash
defaults delete "application"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Thomas Wünsche](mailto:42999314+thomaswuensche@users.noreply.github.com) | defaults: add find example (#5147) | 2021-01-16T15:04:01 | [7f63c6eee9bc](https://github.com/tldr-pages/tldr/commit/7f63c6eee9bc2645e962174abc59999a2985da7b)
[Daniel Bayley](mailto:daniel.bayley@me.com) | Update macOS references Update references to 'OS X' to 'macOS'. | 2017-07-28T17:43:30 | [8ce4c60a4454](https://github.com/tldr-pages/tldr/commit/8ce4c60a445464f68e8e3cfa7480e97f41880d76)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Linting | 2016-02-13T00:35:42 | [61a3795b6aee](https://github.com/tldr-pages/tldr/commit/61a3795b6aee6cd0e9dd9b9982b42e06d9270588)
[Leandro Ostera](mailto:leandro@ostera.io) | Kept the speed up sample...more below Some text changes to make it more user-friendly. Naturally this is up for discussion. | 2016-02-13T00:22:07 | [50ba02aa36db](https://github.com/tldr-pages/tldr/commit/50ba02aa36dbf50350e9e4710b7d5d6df422e2a0)
[sfarzy](mailto:salmanulfarzy@gmail.com) | defaults: Included domain attribute domain attrribute to access system defaults example for default write added | 2016-01-01T23:24:20 | [2177d2b75217](https://github.com/tldr-pages/tldr/commit/2177d2b7521747fabc2a537f7efa93ef57537649)
[sfarzy](mailto:salmanulfarzy@gmail.com) | defaults: delete error updated | 2016-01-01T09:07:09 | [0c227cca56d3](https://github.com/tldr-pages/tldr/commit/0c227cca56d3d0be8b490abc5c6db8e72308d248)
[sfarzy](mailto:salmanulfarzy@gmail.com) | defaults: add page | 2015-12-30T19:45:24 | [55d37a3030e0](https://github.com/tldr-pages/tldr/commit/55d37a3030e095e08d5655ab57cbece01a5b6ca3)

