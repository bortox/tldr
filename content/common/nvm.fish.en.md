---
author: ['Reinhart Previano Koentjoro']
date: 1641501829
title: "nvm"
description: "nvm, Install, uninstall, or switch between Node.js versions under the `fish` shell."
categories: "common"
---
> Supports version numbers like "12.8" or "v16.13.1", and labels like "stable", "system", etc.

> More information: <https://github.com/jorgebucaran/nvm.fish>.

- Install a specific version of Node.js:

```bash
nvm install node_version
```

- Use a specific version of Node.js in the current shell:

```bash
nvm use node_version
```

- Set the default Node.js version:

```bash
set nvm_default_version node_version
```

- List all available Node.js versions and highlight the default one:

```bash
nvm list
```

- Uninstall a given Node.js version:

```bash
nvm uninstall node_version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | nvm.fish: add page (#7512) | 2022-01-06T21:43:49 | [6a483fda5777](https://github.com/tldr-pages/tldr/commit/6a483fda57773795240381ed8b565f3cde63d4a2)

