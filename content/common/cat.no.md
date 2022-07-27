---
author: ['erlendmoland']
date: 1635359898
title: "cat, TLDR Pages"
description: "cat, Skriv ut og sammenføy filer."
categories: "common"
---
> Mer informasjon: <https://www.gnu.org/software/coreutils/cat>.

- Skriv ut innholdet i en fil til standard utgang:

```bash
cat fil
```

- Sammenføy flere filer til en målfil:

```bash
cat fil1 fil2 > målfil
```

- Legg til flere filer til målfilen:

```bash
cat fil1 fil2 >> målfil
```

- Nummerer alle utgangslinjer:

```bash
cat -n fil
```

- Vis tegn som ikke kan skrives ut og mellomrom (med `M-` prefiks hvis det ikke er ASCII-tegn):

```bash
cat -v -t -e fil
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[erlendmoland](mailto:56839803+erlendmoland@users.noreply.github.com) | cat: add Norwegian translation (#7172) | 2021-10-27T20:38:18 | [d974303e2ec8](https://github.com/tldr-pages/tldr/commit/d974303e2ec896e14108e611c82698610bb562b3)

