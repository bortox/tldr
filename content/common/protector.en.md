---
author: ['Nicolas Kosinski']
date: 1619326801
title: "protector, TLDR Pages"
description: "protector, Protect or unprotect branches on GitHub repositories."
categories: "common"
---
> More information: <https://github.com/jcgay/protector>.

- Protect branches of a GitHub repository (create branch protection rules):

```bash
protector branches_regex -repos organization/repository
```

- Use the dry run to see what would be protected (can also be used for freeing):

```bash
protector -dry-run branches_regex -repos organization/repository
```

- Free branches of a GitHub repository (delete branch protection rules):

```bash
protector -free branches_regex -repos organization/repository
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | protector: add page (#5820) | 2021-04-25T07:00:01 | [1a47a2612f50](https://github.com/tldr-pages/tldr/commit/1a47a2612f50887610b860debf729bcc067a4901)

