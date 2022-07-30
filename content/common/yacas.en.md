---
author: ['Daniel Birket']
date: 1627890181
title: "yacas"
description: "yacas, Yet Another Computer Algebra System."
categories: "common"
---
> More information: <http://www.yacas.org>.

- Start an interactive `yacas` session:

```bash
yacas
```

- While in a `yacas` session, execute a statement:

```bash
Integrate(x)Cos(x);
```

- While in a `yacas` session, display an example:

```bash
Example();
```

- Quit from a `yacas` session:

```bash
quit
```

- Execute one or more `yacas` scripts (without terminal or prompts), then exit:

```bash
yacas -p -c path/to/script1 path/to/script2
```

- Execute and print the result of one statement, then exit:

```bash
echo "Echo( Deriv(x)Cos(1/x) );" | yacas -p -c /dev/stdin
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Daniel Birket](mailto:danielb@birket.com) | yacas: add page (#6263) | 2021-08-02T09:43:01 | [eaef3b4d2111](https://github.com/tldr-pages/tldr/commit/eaef3b4d2111a816b416eaecfe7d87641c274d1a)

