---
author: ['ciph3rz']
date: 1635543021
title: "chntpw, TLDR Pages"
description: "chntpw, A utility that can edit windows registry, reset user password, promote users to administrator by modifying the Windows SAM."
categories: "linux"
---
> Boot target machine with live cd like Kali Linux and run with elevated privileges.

> More information: <http://pogostick.net/~pnh/ntpasswd>.

- List all users in the SAM file:

```bash
chntpw -l path/to/sam_file
```

- Edit [u]ser interactively:

```bash
chntpw -u username path/to/sam_file
```

- Use chntpw [i]nteractively:

```bash
chntpw -i path/to/sam_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[ciph3rz](mailto:46655414+ciph3rz@users.noreply.github.com) | chntpw: add page (#7248) | 2021-10-29T23:30:21 | [cb559cbad88b](https://github.com/tldr-pages/tldr/commit/cb559cbad88b7e5bea52ea76d6b4077673846118)

