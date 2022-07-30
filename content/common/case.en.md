---
author: ['Colin', 'marchersimon']
date: 1618756407
title: "case"
description: "case, Branch based on the value of an expression."
categories: "common"
---
> More information: <https://manned.org/case>.

- Match a variable against string literals to decide which command to run:

```bash
case $tocount in words) wc -w README; ;; lines) wc -l README; ;; esac
```

- Combine patterns with |, use * as a fallback pattern:

```bash
case $tocount in [wW]|words) wc -w README; ;; [lL]|lines) wc -l README; ;; *) echo "what?"; ;; esac
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | case: add link | 2021-04-18T16:33:27 | [4d87a4e1a562](https://github.com/tldr-pages/tldr/commit/4d87a4e1a562f8aa1581c21aa263994d3c5078fa)
[Colin](mailto:colin.morris2@gmail.com) | case: add page (#1930) | 2018-02-20T21:58:20 | [81ac166eed3c](https://github.com/tldr-pages/tldr/commit/81ac166eed3c43ffe4fb7c29bdd88068b2037f07)

