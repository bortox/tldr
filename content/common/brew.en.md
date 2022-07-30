---
author: ['Nicolas Kosinski']
date: 1618082540
title: "brew"
description: "brew, Package manager for macOS and Linux."
categories: "common"
---
> More information: <https://brew.sh>.

- Install the latest stable version of a formula or cask (use `--devel` for development versions):

```bash
brew install formula
```

- List all installed formulae and casks:

```bash
brew list
```

- Upgrade an installed formula or cask (if none is given, all installed formulae/casks are upgraded):

```bash
brew upgrade formula
```

- Fetch the newest version of Homebrew and of all formulae and casks from the Homebrew source repository:

```bash
brew update
```

- Show formulae and casks that have a more recent version available:

```bash
brew outdated
```

- Search for available formulae (i.e. packages) and casks (i.e. native packages):

```bash
brew search text
```

- Display information about a formula or a cask (version, installation path, dependencies, etc.):

```bash
brew info formula
```

- Check the local Homebrew installation for potential problems:

```bash
brew doctor
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | brew: make a common page for macOS, Linux and Windows (#5693) | 2021-04-10T21:22:20 | [b4744ecf21ed](https://github.com/tldr-pages/tldr/commit/b4744ecf21edd51ea1a2e1d616dd9d6dcb1d321d)

