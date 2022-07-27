---
author: ['Owen Voke']
date: 1567685593
title: "act, TLDR Pages"
description: "act, Execute GitHub Actions locally using Docker."
categories: "common"
---
> More information: <https://github.com/nektos/act>.

- List the available actions:

```bash
act -l
```

- Run the default event:

```bash
act
```

- Run a specific event:

```bash
act event_type
```

- Run a specific action:

```bash
act -a action_id
```

- Do not actually run the actions (i.e. a dry run):

```bash
act -n
```

- Show verbose logs:

```bash
act -v
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:owzie123@gmail.com) | act: add page (#3257) | 2019-09-05T14:13:13 | [5058a09516a4](https://github.com/tldr-pages/tldr/commit/5058a09516a4a0a78bafd09d0160632f41149cf4)

