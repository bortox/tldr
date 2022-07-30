---
author: ['Tsvetomir Bonev']
date: 1632671818
title: "git secret"
description: "git secret, Bash tool which stores private data inside a Git repository."
categories: "common"
---
> More information: <https://github.com/sobolevn/git-secret>.

- Initialize `git-secret` in a local repository:

```bash
git secret init
```

- Grant access to the current Git user's email:

```bash
git secret tell -m
```

- Grant access by email:

```bash
git secret tell email
```

- Revoke access by email:

```bash
git secret killperson email
```

- List emails with access to secrets:

```bash
git secret whoknows
```

- Register a secret file:

```bash
git secret add path/to/file
```

- Encrypt secrets:

```bash
git secret hide
```

- Decrypt secret files:

```bash
git secret reveal
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Tsvetomir Bonev](mailto:invakid404@riseup.net) | git-secret: add page (#6589) | 2021-09-26T17:56:58 | [ac20da70b329](https://github.com/tldr-pages/tldr/commit/ac20da70b329b1ee2605d424551c2b2789c6b34f)

