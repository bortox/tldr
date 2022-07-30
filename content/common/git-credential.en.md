---
author: ['bl-ue']
date: 1610812956
title: "git credential"
description: "git credential, Retrieve and store user credentials."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-credential>.

- Display credential information, retrieving the username and password from configuration files:

```bash
echo "url=http://example.com" | git credential fill
```

- Send credential information to all configured credential helpers to store for later use:

```bash
echo "url=http://example.com" | git credential approve
```

- Erase the specified credential information from all the configured credential helpers:

```bash
echo "url=http://example.com" | git credential reject
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | git-credential: add page (#5115) * git-credential: add page * Apply suggestions from code review Co-authored-by: Starbeamrainbowlabs [...] | 2021-01-16T17:02:36 | [69e699ec238a](https://github.com/tldr-pages/tldr/commit/69e699ec238a59ae1f5a7923c006ce0f9cbd2d62)

