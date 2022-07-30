---
author: ['Waldir Pimenta', 'Karthikeyan Vaithilingam']
date: 1609242414
title: "choice"
description: "choice, Prompts the user to select one item from a list of single-character choices in a batch program, and then returns the index of the selected choice."
categories: "windows"
---
> If used without parameters, choice displays the default choices Y and N.

> More information: <https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/choice>.

- A,B and C as list of choices to be used:

```bash
choice /c ABC
```

- Use the default [Y,N] list of choices:

```bash
choice
```

- Specify that the choices are case-sensitive:

```bash
choice /CS AaBb
```

- Specify the number of seconds to pause before using the default choice specified by `/d`:

```bash
choice /C AaBb /t 3 /d b
```

- Specify a message to display before the list of choices. If `/m` is not specified, only the choice prompt is displayed:

```bash
choice /m message /C ABC
```

- Display help message:

```bash
choice /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Fix syntax of "More information" links (#5050) | 2020-12-29T12:46:54 | [5430739f1dc4](https://github.com/tldr-pages/tldr/commit/5430739f1dc4d29b85b838e594550ba6c133001f)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | choice: add page (#4677) | 2020-10-19T17:38:32 | [0a244217b746](https://github.com/tldr-pages/tldr/commit/0a244217b746f43af96b4c080d505f7470c259f4)

