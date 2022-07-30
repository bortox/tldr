---
author: ['Evan Boehs', 'Red Headphone', 'Joachim Schwarm']
date: 1634801299
title: "nodemon"
description: "nodemon, Watch files and automatically restart a node application when changes are detected."
categories: "common"
---
> More information: <https://nodemon.io>.

- Execute the specified file and watch a specific file for changes:

```bash
nodemon path/to/file.js
```

- Manually restart nodemon (note nodemon must already be active for this to work):

```bash
rs
```

- Ignore specific files:

```bash
nodemon --ignore path/to/file_or_directory
```

- Pass arguments to the node application:

```bash
nodemon path/to/file.js arguments
```

- Pass arguments to node itself if they're not nodemon arguments already (e.g. `--inspect`):

```bash
nodemon arguments path/to/file.js
```

- Run an arbitrary non-node script:

```bash
nodemon --exec "command_to_run_script options" path/to/script
```

- Run a Python script:

```bash
nodemon --exec "python options" path/to/file.py
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Red Headphone](mailto:55500003+RedHeadphone@users.noreply.github.com) | nodemon: change python example to general example (#6956) | 2021-10-21T09:28:19 | [07d3869a8351](https://github.com/tldr-pages/tldr/commit/07d3869a83517074a4900a7c48a0f44c744cc355)
[Joachim Schwarm](mailto:joachim@schwarm.co) | nodemon: make --inspect a generic example (#6629) | 2021-10-03T22:23:26 | [c3e6980895f7](https://github.com/tldr-pages/tldr/commit/c3e6980895f76b295d9eb43174618891290a2a8b)
[Evan Boehs](mailto:evanboehs@gmail.com) | nodemon: add page (#4308) | 2020-09-09T01:45:43 | [48074e07e3c3](https://github.com/tldr-pages/tldr/commit/48074e07e3c3a981701dd200378d349b2f208e90)

