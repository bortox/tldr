---
author: ['Emily Grace Seville']
date: 1639856769
title: "local"
description: "local, Declare local variables and give them attributes."
categories: "common"
---
> More information: <https://www.gnu.org/software/bash/manual/bash.html#Bash-Builtins>.

- Declare a string variable with the specified value:

```bash
local variable="value"
```

- Declare an integer variable with the specified value:

```bash
local -i variable="value"
```

- Declare an array variable with the specified value:

```bash
local variable=(item_a item_b item_c)
```

- Declare an associative array variable with the specified value:

```bash
local -A variable=([key_a]=item_a [key_b]=item_b [key_c]=item_c)
```

- Declare a readonly variable with the specified value:

```bash
local -r variable="value"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | declare, local, typeset: add pages (#7529) | 2021-12-18T20:46:09 | [dea25fb85add](https://github.com/tldr-pages/tldr/commit/dea25fb85add59a3d75df3df9822f7b7c803c755)

