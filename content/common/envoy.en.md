---
author: ['Seth Falco', 'Owen Voke']
date: 1656325392
title: "envoy, TLDR Pages"
description: "envoy, A PHP-based task manager for Laravel remote servers."
categories: "common"
---
> More information: <https://laravel.com/docs/envoy>.

- Initialize a configuration file:

```bash
envoy init host_name
```

- Run a task:

```bash
envoy run task_name
```

- Run a task from a specific project:

```bash
envoy run --path path/to/directory task_name
```

- Run a task and continue on failure:

```bash
envoy run --continue task_name
```

- Dump a task as a Bash script for inspection:

```bash
envoy run --pretend task_name
```

- Connect to the specified server via SSH:

```bash
envoy ssh server_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Owen Voke](mailto:owzie123@gmail.com) | envoy: add page | 2019-08-05T14:03:11 | [537075f96e91](https://github.com/tldr-pages/tldr/commit/537075f96e918782d4dc99289dff45dc803d2b06)

