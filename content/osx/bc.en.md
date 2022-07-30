---
author: ['Emily Grace Seville']
date: 1642831209
title: "bc"
description: "bc, An arbitrary precision calculator language."
categories: "osx"
---
> See also: `dc`.

> More information: <https://manned.org/man/freebsd-13.0/bc.1>.

- Start an interactive session:

```bash
bc
```

- Start an interactive session with the standard math library enabled:

```bash
bc --mathlib
```

- Calculate an expression:

```bash
bc --expression='5 / 3'
```

- Execute a script:

```bash
bc path/to/script.bc
```

- Calculate an expression with the specified scale:

```bash
bc --expression='scale = 10; 5 / 3'
```

- Calculate a sine/cosine/arctangent/natural logarithm/exponential function using `mathlib`:

```bash
bc --mathlib --expression='s|c|a|l|e(1)'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | bc, dc: refresh page (#7670) | 2022-01-22T07:00:09 | [47445dd78609](https://github.com/tldr-pages/tldr/commit/47445dd7860917026b4df1845f4c54a0f3d6ab94)

