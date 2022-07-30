---
author: ['Caden Haustein']
date: 1610826099
title: "ghcup"
description: "ghcup, Haskell toolchain installer."
categories: "common"
---
> Install, manage, and update Haskell toolchains.

> More information: <https://gitlab.haskell.org/haskell/ghcup-hs>.

- Start the interactive TUI:

```bash
ghcup tui
```

- List available GHC/cabal versions:

```bash
ghcup list
```

- Install the recommended GHC version:

```bash
ghcup install ghc
```

- Install a specific GHC version:

```bash
ghcup install ghc version
```

- Set the currently "active" GHC version:

```bash
ghcup set ghc version
```

- Install cabal-install:

```bash
ghcup install cabal
```

- Update `ghcup` itself:

```bash
ghcup upgrade
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Caden Haustein](mailto:code@brightlysalty.33mail.com) | ghcup: add page (#5145) * ghcup: add page * Update pages/common/ghcup.md Co-authored-by: bl-ue <54780737+bl- [...] | 2021-01-16T20:41:39 | [c23a73b84ebb](https://github.com/tldr-pages/tldr/commit/c23a73b84ebbcec2bbbc83f229946bda46ebfc82)

