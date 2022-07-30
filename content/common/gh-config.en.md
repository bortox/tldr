---
author: ['Axel Navarro', 'Mateusz Soszyński']
date: 1615833276
title: "gh config"
description: "gh config, Change configuration for GitHub cli."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_config>.

- Display what Git protocol is being used:

```bash
gh config get git_protocol
```

- Set protocol to SSH:

```bash
gh config set git_protocol ssh
```

- Use `delta` in side-by-side mode as the default pager for all `gh` commands:

```bash
gh config set pager 'delta --side-by-side'
```

- Set text editor to Vim:

```bash
gh config set editor vim
```

- Reset to default text editor:

```bash
gh config set editor ""
```

- Disable interactive prompts:

```bash
gh config set prompt disabled
```

- Set a specific configuration value:

```bash
gh config set key value
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-config: add set pager example (#5448) | 2021-03-15T19:34:36 | [4968284965f3](https://github.com/tldr-pages/tldr/commit/4968284965f3be5ab327fd316e8b30db490a8083)
[Mateusz Soszyński](mailto:mateusz.soszynski@tuta.io) | gh-config: add page (#4837) | 2020-10-27T11:38:49 | [25ca1ccce8ea](https://github.com/tldr-pages/tldr/commit/25ca1ccce8eae6e002c20dfae8b8e69fd804602d)

