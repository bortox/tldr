---
author: ['bl-ue']
date: 1607750506
title: "from"
description: "from, Prints mail header lines from the current user's mailbox."
categories: "common"
---
> More information: <https://mailutils.org/manual/html_chapter/Programs.html#frm-and-from>.

- List mail:

```bash
from
```

- Display the number of messages stored:

```bash
from --count
```

- List mail in the specified mailbox directory:

```bash
MAIL=path/to/mailbox from
```

- Print the mail from the specified address:

```bash
from --sender=me@example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | from: add page (#5011) | 2020-12-12T06:21:46 | [1d9c989711b1](https://github.com/tldr-pages/tldr/commit/1d9c989711b173580229d66ebdadc06239c5cca6)

