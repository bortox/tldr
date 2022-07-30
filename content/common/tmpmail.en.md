---
author: ['Gianni Young']
date: 1608297725
title: "tmpmail"
description: "tmpmail, A temporary email right from your terminal written in POSIX sh."
categories: "common"
---
> More information: <https://github.com/sdushantha/tmpmail>.

- Create a temporary inbox:

```bash
tmpmail --generate
```

- List messages and their numeric ID:

```bash
tmpmail
```

- Display the most recent received email:

```bash
tmpmail --recent
```

- Open a specific message:

```bash
tmpmail email_id
```

- View email as raw text without HTML tags:

```bash
tmpmail --text
```

- Open email with a specific browser (default is w3m):

```bash
tmpmail --browser browser
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gianni Young](mailto:43043456+GianniBYoung@users.noreply.github.com) | tmpmail: add page (#5026) * tmpmail: add page * Update tmpmail.md * Update tmpmail.md * Update pages/common/tmpmail.md Co-authored-by: [...] | 2020-12-18T14:22:05 | [abd16f124c04](https://github.com/tldr-pages/tldr/commit/abd16f124c04f03164f98b0c703f1f9155246ba0)

