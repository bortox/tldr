---
author: ['Waldir Pimenta', 'Bill Flynn', 'Pradeep Reddy Raamana', 'Muhammad Falak R Wani', 'Dario Vladović', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1617292466
title: "seq, TLDR Pages"
description: "seq, Output a sequence of numbers to stdout."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/seq>.

- Sequence from 1 to 10:

```bash
seq 10
```

- Every 3rd number from 5 to 20:

```bash
seq 5 3 20
```

- Separate the output with a space instead of a newline:

```bash
seq -s " " 5 3 20
```

- Format output width to a minimum of 4 digits padding with zeros as necessary:

```bash
seq -f "%04g" 5 3 20
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | seq: add link (#5625) | 2021-03-30T16:00:58 | [e773c61881d3](https://github.com/tldr-pages/tldr/commit/e773c61881d3fd4403afe138c894e52cfea50aad)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | Update pages/common/seq.md Co-Authored-By: wflynny <wflynny@gmail.com> | 2018-12-03T23:25:22 | [bec17702b4e9](https://github.com/tldr-pages/tldr/commit/bec17702b4e9892a4f93b40b046598937ec6b04c)
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | Update pages/common/seq.md Co-Authored-By: wflynny <wflynny@gmail.com> | 2018-12-03T23:25:22 | [98d8163c0d89](https://github.com/tldr-pages/tldr/commit/98d8163c0d89a4320eeb48f5b179e2d11238d44e)
[Bill Flynn](mailto:wflynny@gmail.com) | seq: add --format example | 2018-12-03T23:25:22 | [eab3df67aeb1](https://github.com/tldr-pages/tldr/commit/eab3df67aeb1a15f21e9c91f484a28834d242bcd)
[Pradeep Reddy Raamana](mailto:raamana@gmail.com) | w: split out of common and add -i to osx, uniq: additions, seq: add page | 2016-01-23T18:03:00 | [525f436cc88c](https://github.com/tldr-pages/tldr/commit/525f436cc88c28ddf4d139d3314dc71b94ddcb24)

