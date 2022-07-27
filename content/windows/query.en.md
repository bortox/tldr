---
author: ['Sebastian Staudt']
date: 1634020342
title: "query, TLDR Pages"
description: "query, Displays information about user sessions and process."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/query>.

- Display all user sessions:

```bash
query session
```

- Display the current user sessions on a remote computer:

```bash
query session /server:hostname
```

- Display logged in users:

```bash
query user
```

- Display all user sessions on a remote computer:

```bash
query session /server:hostname
```

- Display all running processes:

```bash
query process
```

- Display running processes by session or user name:

```bash
query process session_name|user_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sebastian Staudt](mailto:koraktor@gmail.com) | query: add page (#6719) | 2021-10-12T08:32:22 | [9cec233eb7e4](https://github.com/tldr-pages/tldr/commit/9cec233eb7e4b745bbf4b38f52e3f9e82b89254d)

