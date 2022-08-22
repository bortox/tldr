---
author: ['Waldir Pimenta', 'Karthikeyan Vaithilingam', 'Emily Grace Seville']
date: 1661065417
title: "choice"
description: "choice, Prompt user to select a choice and return the selected choice index."
categories: "windows"
---
> More information: <https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/choice>.

- Prompt the current user to select a `Y` or `N` choice:

```bash
choice
```

- Prompt the current user to select a [c]hoice from a specific set:

```bash
choice /c AB
```

- Prompt the current user to select a choice with a specific [m]essage:

```bash
choice /m "message"
```

- Prompt the current user to select a [c]ase-[s]ensitive [c]hoice from a specific set:

```bash
choice /cs /c Ab
```

- Prompt the current user to select a choice and prefer the [d]efault choice in a specific [t]ime:

```bash
choice /t 5 /d N
```

- Display help:

```bash
choice /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | choice: update page (#8351) * Refresh choice.md * Fix help example * Fix syntax error * Fix grammar error Co-authored-by: [...] | 2022-08-21T09:03:37 | [fc968a715da2](https://github.com/tldr-pages/tldr/commit/fc968a715da2087cfb82bc02ffd086dad5ddaae8)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Fix syntax of "More information" links (#5050) | 2020-12-29T12:46:54 | [5430739f1dc4](https://github.com/tldr-pages/tldr/commit/5430739f1dc4d29b85b838e594550ba6c133001f)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | choice: add page (#4677) | 2020-10-19T17:38:32 | [0a244217b746](https://github.com/tldr-pages/tldr/commit/0a244217b746f43af96b4c080d505f7470c259f4)

