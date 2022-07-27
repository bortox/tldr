---
author: ['shreyasm-dev']
date: 1634267314
title: "xcrun, TLDR Pages"
description: "xcrun, Run or locate development tools and properties."
categories: "osx"
---
> More information: <https://www.unix.com/man-page/osx/1/xcrun/>.

- Find and run a tool from the active developer directory:

```bash
xcrun tool arguments
```

- Show verbose output:

```bash
xcrun tool arguments --verbose
```

- Find a tool for a given SDK:

```bash
xcrun --sdk sdk_name
```

- Find a tool for a given toolchain:

```bash
xcrun --toolchain name
```

- Display help:

```bash
xcrun --help
```

- Display version:

```bash
xcrun --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[shreyasm-dev](mailto:62489066+shreyasm-dev@users.noreply.github.com) | xcrun: add page (#6618) | 2021-10-15T05:08:34 | [037a9d30859d](https://github.com/tldr-pages/tldr/commit/037a9d30859d4be491673325d57d23e1f97d99f6)

