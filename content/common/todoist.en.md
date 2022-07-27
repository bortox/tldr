---
author: ['iulian']
date: 1629042774
title: "todoist, TLDR Pages"
description: "todoist, Access Todoist from the command-line."
categories: "common"
---
> More information: <https://github.com/sachaos/todoist>.

- Add a task:

```bash
todoist add "task_name"
```

- Add a high priority task with a label, project, and due date:

```bash
todoist add "task_name" --priority 1 --label-ids "label_id" --project-name "project_name" --date "tmr 9am"
```

- Add a high priority task with a label, project, and due date in quick mode:

```bash
todoist quick '#project_name "tmr 9am" p1 task_name @label_name'
```

- List all tasks with a header and color:

```bash
todoist --header --color list
```

- List all high priority tasks:

```bash
todoist list --filter p1
```

- List today's tasks with high priority that have the specified label:

```bash
todoist list --filter '(@label_name | today) & p1'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[iulian](mailto:iulian.dita@gmail.com) | todoist: add page (#6361) | 2021-08-15T17:52:54 | [24ba08b5ed1b](https://github.com/tldr-pages/tldr/commit/24ba08b5ed1b4e56a916319f3e2292c31f569885)

