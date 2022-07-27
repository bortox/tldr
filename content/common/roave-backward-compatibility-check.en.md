---
author: ['Lucas Gabriel Schneider', 'Owen Voke']
date: 1609242305
title: "roave-backward-compatibility-check, TLDR Pages"
description: "roave-backward-compatibility-check, A tool that can be used to verify backward compatibility breaks between two versions of a PHP library."
categories: "common"
---
> More information: <https://github.com/Roave/BackwardCompatibilityCheck>.

- Check for breaking changes since the last tag:

```bash
roave-backward-compatibility-check
```

- Check for breaking changes since a specific tag:

```bash
roave-backward-compatibility-check --from=git_reference
```

- Check for breaking changes between the last tag and a specific reference:

```bash
roave-backward-compatibility-check --to=git_reference
```

- Check for breaking changes and output to Markdown:

```bash
roave-backward-compatibility-check --format=markdown > results.md
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | change markdown to Markdown (#5049) | 2020-12-29T12:45:05 | [8b80cf08b84a](https://github.com/tldr-pages/tldr/commit/8b80cf08b84aec781c99c2a42c7acf95bab446cf)
[Owen Voke](mailto:owzie123@gmail.com) | roave-backward-compatibility-check: add page (#3105) | 2019-06-12T23:01:31 | [f6e4f3450dcb](https://github.com/tldr-pages/tldr/commit/f6e4f3450dcb5763c73182971d0850e8c120b925)

