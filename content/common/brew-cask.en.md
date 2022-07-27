---
author: ['marchersimon']
date: 1631516812
title: "brew cask, TLDR Pages"
description: "brew cask, Package manager for macOS applications distributed as binaries."
categories: "common"
---
> More information: <https://github.com/Homebrew/homebrew-cask>.

- Search for formulas and casks:

```bash
brew search text
```

- Install a cask:

```bash
brew cask install cask_name
```

- List all installed casks:

```bash
brew list --cask
```

- List installed casks that have newer versions available:

```bash
brew outdated --cask
```

- Upgrade an installed cask (if no cask name is given, all installed casks are upgraded):

```bash
brew upgrade --cask cask_name
```

- Uninstall a cask:

```bash
brew cask uninstall cask_name
```

- Uninstall a cask and remove related settings and files:

```bash
brew cask zap cask_name
```

- Display information about a given cask:

```bash
brew cask info cask_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | brew*: move to common (#6507) | 2021-09-13T09:06:52 | [4fbb601f63ee](https://github.com/tldr-pages/tldr/commit/4fbb601f63ee14b0ed9a23d1d9c78bb102a23776)

