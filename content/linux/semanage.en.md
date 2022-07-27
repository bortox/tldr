---
author: ['Michael Wade', 'marchersimon']
date: 1618584134
title: "semanage, TLDR Pages"
description: "semanage, SELinux Policy Management tool."
categories: "linux"
---
> More information: <https://manned.org/semanage>.

- Output local customizations:

```bash
semanage -S store -o path/to/output_file
```

- Take a set of commands from a specified file and load them in a single transaction:

```bash
semanage -S store -i path/to/input_file
```

- Manage booleans. Booleans allow the administrator to modify the confinement of processes based on the current configuration:

```bash
semanage boolean -S store --delete|--modify|--list|--noheading|--deleteall -on|-off -F boolean|boolean_file
```

- Manage policy modules:

```bash
semanage module -S store --add|--delete|--list|--modify --enable|--disable module_name
```

- Disable/Enable dontaudit rules in policy:

```bash
semanage dontaudit -S store on|off
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Michael Wade](mailto:4274104+savvyspoon@users.noreply.github.com) | semanage: add page (#4353) | 2020-10-17T11:41:23 | [10a79e10fe10](https://github.com/tldr-pages/tldr/commit/10a79e10fe102d8eea69cce38cec2ec37610448a)

