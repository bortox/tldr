---
author: ['Ennio Mara']
date: 1634637524
title: "rm"
description: "rm, Ta bort filer eller mappar."
categories: "common"
---
> Mer information: <https://www.gnu.org/software/coreutils/rm>.

- Ta bort filer från godtyckliga ställen:

```bash
rm sökväg/till/fil sökväg/till/en/annan/fil
```

- Rekursivt ta bort en mapp och dess undermappar:

```bash
rm -r sökväg/till/mapp
```

- Tvinga borttagning av en mapp utan att bekräfta eller visa felmeddelanden:

```bash
rm -rf sökväg/till/mapp
```

- Interaktivt ta bort flera filer, genom att fråga om borttagning för varje fil:

```bash
rm -i fil(er)
```

- Ta bort filer och visa ett meddelande för varje borttagning:

```bash
rm -v sökväg/till/mapp/*
```
Förteckning över ändringar som gjorts i den här dokumentationen


Författare | Beskrivning | ISO 8601 datumformat | Länk till GitHub
------|-----|-----|-----
[Ennio Mara](mailto:enniomara@users.noreply.github.com) | rm: add Swedish translation (#6981) | 2021-10-19T11:58:44 | [67dd1fab50df](https://github.com/tldr-pages/tldr/commit/67dd1fab50df8fb563be856023e1f147181b3af6)

