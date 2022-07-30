---
author: ['Guido Lena Cota', 'Emily Grace Seville', 'Caio Amaral Corrêa']
date: 1644837703
title: "icalBuddy"
description: "icalBuddy, Command-line utility for printing events and tasks from the macOS calendar database."
categories: "osx"
---
> More information: <https://hasseg.org/icalBuddy/>.

- Show events later today:

```bash
icalBuddy -n eventsToday
```

- Show uncompleted tasks:

```bash
icalBuddy uncompletedTasks
```

- Show a formatted list separated by calendar for all events today:

```bash
icalBuddy -f -sc eventsToday
```

- Show tasks for a specified number of days:

```bash
icalBuddy -n "tasksDueBefore:today+days"
```

- Show events in a time range:

```bash
icalBuddy eventsFrom:start_date to:end_date
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Caio Amaral Corrêa](mailto:caiobep@me.com) | icalbuddy: fix typo and simplified commands (#4094) | 2020-06-11T15:48:33 | [b190bed0429c](https://github.com/tldr-pages/tldr/commit/b190bed0429c16503997ea5e322f5f3b6357fad9)
[Caio Amaral Corrêa](mailto:caiobep.dev@gmail.com) | icalbuddy: add page (#4033) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> | 2020-05-10T20:18:33 | [34a6ca632cc4](https://github.com/tldr-pages/tldr/commit/34a6ca632cc4d6e846c0148e5c5a25892e6fa145)

