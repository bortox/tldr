---
author: ['Martin Matous']
date: 1650903829
title: "pw-cli"
description: "pw-cli, The PipeWire Command Line Interface."
categories: "linux"
---
> More information: <https://docs.pipewire.org/page_man_pw_cli_1.html>.

- Print all nodes (sinks and sources) along with their IDs:

```bash
pw-cli list-objects Node
```

- Print information about an object with a specific ID:

```bash
pw-cli info 4
```

- Print all objects' information:

```bash
pw-cli info all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Martin Matous](mailto:18654729+mmatous@users.noreply.github.com) | pw-cli: add page (#8029) * pw-cli: add page Signed-off-by: Martin Matous <m@matous.dev> * Update pages/linux/pw-cli.md Co-authored-by: [...] | 2022-04-25T18:23:49 | [7abb9d313de8](https://github.com/tldr-pages/tldr/commit/7abb9d313de84c00f4d20b721a377c34c26564e3)

