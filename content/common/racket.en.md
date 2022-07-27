---
author: ['Winston (Winny) Weinert']
date: 1634041046
title: "racket, TLDR Pages"
description: "racket, Racket language interpreter."
categories: "common"
---
> More information: <https://racket-lang.org>.

- Start a REPL (interactive shell):

```bash
racket
```

- Execute a Racket script:

```bash
racket path/to/script.rkt
```

- Execute a Racket expression:

```bash
racket --eval "expression"
```

- Run module as a script (terminates option list):

```bash
racket --lib module_name --main arguments
```

- Start a REPL (interactive shell) for the `typed/racket` hashlang:

```bash
racket -I typed/racket
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Winston (Winny) Weinert](mailto:winston@ml1.net) | racket: add page (#6880) | 2021-10-12T14:17:26 | [d89c97f0e1a8](https://github.com/tldr-pages/tldr/commit/d89c97f0e1a833613498cd338c4add95c0201139)

