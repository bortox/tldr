---
author: ['AnimiVulpis', 'Sadeed']
date: 1634106170
title: "roll"
description: "roll, Rolls a user-defined dice sequence."
categories: "common"
---
> More information: <https://manned.org/roll>.

- Roll 3 6-sided dice and sums the results:

```bash
roll 3d
```

- Roll 1 8-sided die, add 3 and sum the results:

```bash
roll d8 + 3
```

- Roll 4 6-sided dice, keep the 3 highest results and sum the results:

```bash
roll 4d6h3
```

- Roll 2 12-sided dice 2 times and show every roll:

```bash
roll --verbose 2{2d12}
```

- Roll 2 20-sided dice until the result is bigger than 10:

```bash
roll "2d20>10"
```

- Roll 2 5-sided dice 3 times and show the total sum:

```bash
roll --sum-series 3{2d5}
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | rar, read, renice, rev, roll, route, rsync: add link (#6929) | 2021-10-13T08:22:50 | [6583ef2421da](https://github.com/tldr-pages/tldr/commit/6583ef2421da704fdb94b1acb67c70936ccb5ddf)
[AnimiVulpis](mailto:animi.vulpis@gmail.com) | Fix tokenization | 2017-10-31T22:47:37 | [0e48d77af102](https://github.com/tldr-pages/tldr/commit/0e48d77af1020d2c8d02bea3080ec34f8e65c43f)
[AnimiVulpis](mailto:animi.vulpis@gmail.com) | Incorporate change requests - Fix wrong usage of dices vs. dice - Tokenize everything | 2017-10-30T23:18:41 | [dacc52d18296](https://github.com/tldr-pages/tldr/commit/dacc52d182967d01feb62b44718cfb66766b8ed0)
[AnimiVulpis](mailto:animi.vulpis@gmail.com) | roll: add page | 2017-10-27T17:41:26 | [28b687062e36](https://github.com/tldr-pages/tldr/commit/28b687062e36cda5846c9c5d69bf822ea8c2ca81)

