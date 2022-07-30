---
author: ['Matt Bangert']
date: 1628016212
title: "choose"
description: "choose, A human-friendly and fast alternative to cut and (sometimes) awk."
categories: "common"
---
> More information: <https://github.com/theryangeary/choose>.

- Print the 5th item from a line (starting from 0):

```bash
choose 4
```

- Print the first, 3rd, and 5th item from a line, where items are separated by ':' instead of whitespace:

```bash
choose --field-separator ':' 0 2 4
```

- Print everything from the 2nd to 5th item on the line, including the 5th:

```bash
choose 1:4
```

- Print everything from the 2nd to 5th item on the line, excluding the 5th:

```bash
choose --exclusive 1:4
```

- Print the beginning of the line to the 3rd item:

```bash
choose :2
```

- Print all items from the beginning of the line until the 3rd item (exclusive):

```bash
choose --exclusive :2
```

- Print all items from the 3rd to the end of the line:

```bash
choose 2:
```

- Print the last item from a line:

```bash
choose -1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Matt Bangert](mailto:mattbangert@gmail.com) | choose: add page (#6135) | 2021-08-03T20:43:32 | [0e9fe32c9e04](https://github.com/tldr-pages/tldr/commit/0e9fe32c9e04ac1e1806cf51989911ca8e084b77)

