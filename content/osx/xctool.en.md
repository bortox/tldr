---
author: ['Waldir Pimenta', 'Owen Voke', 'IgnazioC', 'Ignazioc', 'Marco Bonelli', 'Ruben Vereecken']
date: 1559564381
title: "xctool"
description: "xctool, Tool for building Xcode projects."
categories: "osx"
---
> More information: <https://github.com/facebook/xctool>.

- Build a single project without any workspace:

```bash
xctool -project YourProject.xcodeproj -scheme YourScheme build
```

- Build a project that is part of a workspace:

```bash
xctool -workspace YourWorkspace.xcworkspace -scheme YourScheme build
```

- Clean, build and execute all the tests:

```bash
xctool -workspace YourWorkspace.xcworkspace -scheme YourScheme clean build test
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add links to homepages (#2891) | 2019-04-12T16:35:50 | [27b40af2d146](https://github.com/tldr-pages/tldr/commit/27b40af2d1469bec662fd9c12e641ba55474b819)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | page format: lowercase command names consistently (#1083) | 2016-09-22T09:03:38 | [107248374447](https://github.com/tldr-pages/tldr/commit/1072483744475ab5a25c87e8eb7ed10c99dd6ed8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[IgnazioC](mailto:ignazioc@gmail.com) | fix typo and example order | 2015-08-20T06:59:07 | [491e6b6cf430](https://github.com/tldr-pages/tldr/commit/491e6b6cf4309b90291b82d9a90d549cecbecfdc)
[Ignazioc](mailto:ignazioc@gmail.com) | Added page for xctool | 2015-08-19T12:11:49 | [da325c0ee838](https://github.com/tldr-pages/tldr/commit/da325c0ee838a06b01499b40b8e83a9d27be4aaf)

