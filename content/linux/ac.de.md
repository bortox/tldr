---
author: ['Thomas Christlieb']
date: 1633745416
title: "ac, TLDR Pages"
description: "ac, Zeigt an, wie lange Benutzer verbunden waren."
categories: "linux"
---
> Weitere Informationen: <https://www.gnu.org/software/acct/manual/accounting.html#ac>.

- Zeigt wie viele Stunden der aktuelle Benutzer verbunden war:

```bash
ac
```

- Zeigt wie viele Stunden jeder Benutzer verbunden war:

```bash
ac --individual-totals
```

- Zeigt wie viele Stunden ein bestimmter Benutzer verbunden war:

```bash
ac --individual-totals nutzername
```

- Zeigt wie viele Stunden ein bestimmter Benutzer pro Tag verbunden war:

```bash
ac --daily-totals --individual-totals nutzername
```

- Zeigt zusätzliche Details:

```bash
ac --compatibility
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Thomas Christlieb](mailto:thomaschristlieb@hotmail.com) | ac: add German translation (#6854) | 2021-10-09T04:10:16 | [88029b67dbd6](https://github.com/tldr-pages/tldr/commit/88029b67dbd69fbcf05f7dd36eaa963412f795af)

