---
author: ['Frans Nylund', 'Emily Grace Seville']
date: 1642277745
title: "declare"
description: "declare, Declare variables and give them attributes."
categories: "common"
---
> More information: <https://www.gnu.org/software/bash/manual/bash.html#Bash-Builtins>.

- Declare a string variable with the specified value:

```bash
declare variable="value"
```

- Declare an integer variable with the specified value:

```bash
declare -i variable="value"
```

- Declare an array variable with the specified value:

```bash
declare -a variable=(item_a item_b item_c)
```

- Declare an associative array variable with the specified value:

```bash
declare -A variable=([key_a]=item_a [key_b]=item_b [key_c]=item_c)
```

- Declare a readonly string variable with the specified value:

```bash
declare -r variable="value"
```

- Declare a global variable within a function with the specified value:

```bash
declare -g variable="value"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Frans Nylund](mailto:frans@fransnylund.com) | declare: fix -a example (#7659) | 2022-01-15T21:15:45 | [b0bef9daba28](https://github.com/tldr-pages/tldr/commit/b0bef9daba289052f874e2d1376013fc32f3596e)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | declare, local, typeset: add pages (#7529) | 2021-12-18T20:46:09 | [dea25fb85add](https://github.com/tldr-pages/tldr/commit/dea25fb85add59a3d75df3df9822f7b7c803c755)

