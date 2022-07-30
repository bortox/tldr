---
author: ['Axel Navarro']
date: 1644113228
title: "turbo"
description: "turbo, High-performance build system for JavaScript and TypeScript codebases."
categories: "common"
---
> See also: `nx`.

> More information: <https://turborepo.org/docs/reference/command-line-reference>.

- Log in using the default web browser with a Vercel account:

```bash
turbo login
```

- Link the current directory to a Vercel organization and enable remote caching:

```bash
turbo link
```

- Build the current project:

```bash
turbo run build
```

- Run a task without concurrency:

```bash
turbo run task_name --concurrency=1
```

- Run a task ignoring cached artifacts and forcibly re-execute all tasks:

```bash
turbo run task_name --force
```

- Run a task in parallel across packages:

```bash
turbo run task_name --parallel --no-cache
```

- Unlink the current directory from your Vercel organization and disable Remote Caching:

```bash
turbo unlink
```

- Generate a Dot graph of a specific task execution (the output file format can be controlled with the filename):

```bash
turbo run task_name --graph=path/to/file.html|jpg|json|pdf|png|svg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | turbo: add page (#7734) | 2022-02-06T03:07:08 | [11ada9c938a1](https://github.com/tldr-pages/tldr/commit/11ada9c938a158620778bcf31e0a258bebc7f361)

