---
author: ['Axel Navarro']
date: 1632927684
title: "gh extension, TLDR Pages"
description: "gh extension, Manage extensions for the GitHub CLI."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_extension>.

- Initialize a new GitHub CLI extension project in a directory of the same name:

```bash
gh extension create extension_name
```

- Install an extension from a GitHub repository:

```bash
gh extension install owner/repository
```

- List installed extensions:

```bash
gh extension list
```

- Upgrade a specific extension:

```bash
gh extension upgrade extension_name
```

- Upgrade all extensions:

```bash
gh extension upgrade --all
```

- List installed extensions:

```bash
gh extension list
```

- Remove an extension:

```bash
gh extension remove extension_name
```

- Display help about a subcommand:

```bash
gh extension subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-extension: add list and remove examples (#6579) | 2021-09-29T17:01:24 | [43f7696ba38e](https://github.com/tldr-pages/tldr/commit/43f7696ba38e347c15985bf571d481e602c84606)
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-extension: add page (#6407) | 2021-08-25T22:56:31 | [df5f5ac08f8c](https://github.com/tldr-pages/tldr/commit/df5f5ac08f8c1c87f1ddd77f5cda67da3f94420c)

