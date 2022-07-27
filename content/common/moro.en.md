---
author: ['Waldir Pimenta', 'Omid Hezaveh', 'pxgamer']
date: 1559676580
title: "moro, TLDR Pages"
description: "moro, Track work time."
categories: "common"
---
> More information: <https://moro.js.org>.

- Invoke `moro` without parameters, to set the current time as the start of the working day:

```bash
moro
```

- Specify a custom time for the start of the working day:

```bash
moro hi 09:30
```

- Invoke `moro` without parameters a second time, to set the current time at the end of the working day:

```bash
moro
```

- Specify a custom time for the end of the working day:

```bash
moro bye 17:30
```

- Add a note on the current working day:

```bash
moro note 3 hours on project Foo
```

- Show a report of time logs and notes for the current working day:

```bash
moro report
```

- Show a report of time logs and notes for all working days on record:

```bash
moro report --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | moro: add link to homepage | 2019-06-04T21:29:40 | [b6dacde42c8f](https://github.com/tldr-pages/tldr/commit/b6dacde42c8f8b9f227711e2efdf417b1de5aa86)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | moro: minor tweaks (#1470) | 2017-09-09T14:50:41 | [a11869186c63](https://github.com/tldr-pages/tldr/commit/a11869186c63db0848badf89aaecd8917fbac84e)
[Omid Hezaveh](mailto:omidfi@users.noreply.github.com) | moro: add page (#1441) | 2017-08-09T21:17:54 | [6f55ac0dec80](https://github.com/tldr-pages/tldr/commit/6f55ac0dec806311ee45da497f646dd64d85d2de)

