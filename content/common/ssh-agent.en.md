---
author: ['syleung', 'Spencer Krum']
date: 1633351190
title: "ssh-agent"
description: "ssh-agent, Spawn an SSH Agent process."
categories: "common"
---
> An SSH Agent holds SSH keys decrypted in memory until removed or the process is killed.

> See also `ssh-add`, which can add and manage keys held by an SSH Agent.

> More information: <https://man.openbsd.org/ssh-agent>.

- Start an SSH Agent for the current shell:

```bash
eval $(ssh-agent)
```

- Kill the currently running agent:

```bash
ssh-agent -k
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/ssh*: add more information link (#6659) | 2021-10-04T14:39:50 | [a092be52d7de](https://github.com/tldr-pages/tldr/commit/a092be52d7ded26ec56154160c90900c6338e76d)
[Spencer Krum](mailto:nibz@spencerkrum.com) | ssh-agent: add page (#3907) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> Co-authored-by: Zlatan Vasović [...] | 2020-03-19T11:34:52 | [c779c21a447d](https://github.com/tldr-pages/tldr/commit/c779c21a447d00dc93d07de01291e96bda29a1eb)

