---
author: ['Axel Navarro', 'Richard Mörbitz']
date: 1635356849
title: "todo"
description: "todo, A simple, standards-based, cli todo manager."
categories: "common"
---
> More information: <https://todoman.readthedocs.io>.

- List startable tasks:

```bash
todo list --startable
```

- Add a new task to the work list:

```bash
todo new thing_to_do --list work
```

- Add a location to a task with a given ID:

```bash
todo edit --location location_name task_id
```

- Show details about a task:

```bash
todo show task_id
```

- Mark tasks with the specified IDs as completed:

```bash
todo done task_id1 task_id2 ...
```

- Delete a task:

```bash
todo delete task_id
```

- Delete done tasks and reset the IDs of the remaining tasks:

```bash
todo flush
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Richard Mörbitz](mailto:richard.moerbitz@tu-dresden.de) | todo: merge page with examples from #7105 (#7231) | 2021-10-27T19:47:29 | [dfa9eebe1c2f](https://github.com/tldr-pages/tldr/commit/dfa9eebe1c2fef1c7fca480d8e44fa1f430db66c)
[Axel Navarro](mailto:navarroaxel@gmail.com) | todo: fix page name | 2021-10-25T22:53:08 | [b956948b6f48](https://github.com/tldr-pages/tldr/commit/b956948b6f482f9fb99e4e44da695d4baea8f31c)

