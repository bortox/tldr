---
author: ['Sadeed', 'Adrien Thebo', 'abactel']
date: 1662083376
title: "task"
description: "task, Command-line to-do list manager."
categories: "common"
---
> More information: <https://taskwarrior.org/docs/>.

- Add a new task which is due tomorrow:

```bash
task add description due:tomorrow
```

- Update a task's priority:

```bash
task task_id modify priority:H|M|L
```

- Complete a task:

```bash
task task_id done
```

- Delete a task:

```bash
task task_id delete
```

- List all open tasks:

```bash
task list
```

- List open tasks due before the end of the week:

```bash
task list due.before:eow
```

- Show a graphical burndown chart, by day:

```bash
task burndown.daily
```

- List all reports:

```bash
task reports
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adrien Thebo](mailto:adrien@lagrange-automation.io) | task: refresh page (#8328) | 2022-09-02T03:49:36 | [d7a077eee63a](https://github.com/tldr-pages/tldr/commit/d7a077eee63a26725662570c18ba0c2bb37d963a)
[Sadeed](mailto:sadeeedw@gmail.com) | task, telnet, tldrl, tput, traceroute, transcode, type: add link (#7038) | 2021-10-23T20:45:06 | [81dc4a1e8016](https://github.com/tldr-pages/tldr/commit/81dc4a1e8016c5621134ebf80724be7d7d67c56a)
[abactel](mailto:abactel@protonmail.com) | task: Increased readability Changed all capital "ID" to lowercase "id", as agnivade asked. | 2017-01-23T20:53:28 | [3f1209a857f8](https://github.com/tldr-pages/tldr/commit/3f1209a857f88e6915c856c73ad6220aad4dbecf)
[abactel](mailto:abactel@protonmail.com) | task: fix grammar Changed 'complete task' to 'mark task as completed' as waldyrious asked. | 2017-01-23T20:53:28 | [d3ba715c239e](https://github.com/tldr-pages/tldr/commit/d3ba715c239e3968f42b478631aa0f1cc003458b)
[abactel](mailto:abactel@protonmail.com) | task: add page | 2017-01-23T20:53:28 | [7dea1421870d](https://github.com/tldr-pages/tldr/commit/7dea1421870d5e382953fbe49f06f23f90916520)

