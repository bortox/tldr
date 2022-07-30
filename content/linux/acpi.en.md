---
author: ['Francisco Moreno Vilchez', 'Ray Voice']
date: 1602538017
title: "acpi"
description: "acpi, Shows battery status or thermal information."
categories: "linux"
---
> More information: <https://sourceforge.net/projects/acpiclient/files/acpiclient/>.

- Show battery information:

```bash
acpi
```

- Show thermal information:

```bash
acpi -t
```

- Show cooling device information:

```bash
acpi -c
```

- Show thermal information in Fahrenheit:

```bash
acpi -tf
```

- Show all information:

```bash
acpi -V
```

- Extract information from `/proc` instead of `/sys`:

```bash
acpi -p
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ray Voice](mailto:33094591+Ray6464@users.noreply.github.com) | acpi: add proc example (#4526) | 2020-10-12T23:26:57 | [9f1c79f1346e](https://github.com/tldr-pages/tldr/commit/9f1c79f1346eb4eb5fe8dc5b2054853a08ff01c0)
[Francisco Moreno Vilchez](mailto:1998morevi@gmail.com) | acpi: add page (#3477) | 2019-11-08T00:43:41 | [46343b157d9d](https://github.com/tldr-pages/tldr/commit/46343b157d9d2866be5fda1183296207da1e9fca)

