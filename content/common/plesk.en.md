---
author: ['Alexei Yuzhakov']
date: 1618000430
title: "plesk"
description: "plesk, Plesk hosting control panel CLI interface."
categories: "common"
---
> More information: <https://docs.plesk.com>.

- Generate an auto login link for the admin user and print it:

```bash
plesk login
```

- Show product version information:

```bash
plesk version
```

- List all hosted domains:

```bash
plesk bin domain --list
```

- Start watching for changes in the `panel.log` file:

```bash
plesk log panel.log
```

- Start the interactive MySQL console:

```bash
plesk db
```

- Open the Plesk main configuration file in the default editor:

```bash
plesk conf panel.ini
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alexei Yuzhakov](mailto:sibprogrammer@gmail.com) | plesk: add page (#5698) | 2021-04-09T22:33:50 | [1c8e7f4342cd](https://github.com/tldr-pages/tldr/commit/1c8e7f4342cddd5233dc13c2cc2b8c31e56c756d)

