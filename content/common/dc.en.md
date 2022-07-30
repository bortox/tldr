---
author: ['Matthew Thompson', 'Emily Grace Seville', 'marchersimon']
date: 1642831209
title: "dc"
description: "dc, An arbitrary precision calculator. Uses reverse polish notation (RPN)."
categories: "common"
---
> See also: `bc`.

> More information: <https://www.gnu.org/software/bc/manual/dc-1.05/html_mono/dc.html>.

- Start an interactive session:

```bash
dc
```

- Execute a script:

```bash
dc path/to/script.dc
```

- Calculate an expression with the specified scale:

```bash
dc --expression='10 k 5 3 / p'
```

- Calculate 4 times 5 (4 5 *), subtract 17 (17 -), and [p]rint the output:

```bash
dc --expression='4 5 * 17 - p'
```

- Set number of decimal places to 7 (7 k), calculate 5 divided by -3 (5 _3 /) and [p]rint:

```bash
dc --expression='7 k 5 _3 / p'
```

- Calculate the golden ratio, phi: set number of decimal places to 100 (100 k), square root of 5 (5 v) plus 1 (1 +), divided by 2 (2 /), and [p]rint result:

```bash
dc --expression='100 k 5 v 1 + 2 / p'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | bc, dc: refresh page (#7670) | 2022-01-22T07:00:09 | [47445dd78609](https://github.com/tldr-pages/tldr/commit/47445dd7860917026b4df1845f4c54a0f3d6ab94)
[marchersimon](mailto:marchersimon@zohomail.eu) | dc: edit link | 2021-04-20T00:05:51 | [12349ec3a507](https://github.com/tldr-pages/tldr/commit/12349ec3a50759fae6bc2a35214f6979650dbd66)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Matthew Thompson](mailto:fortran@gmail.com) | Consistent use of k operator | 2017-12-17T22:47:56 | [757901f9a099](https://github.com/tldr-pages/tldr/commit/757901f9a099cb43dbbc04505b9df726225ee5d1)
[Matthew Thompson](mailto:fortran@gmail.com) | Fix typo | 2017-12-16T21:18:43 | [38fa3557692f](https://github.com/tldr-pages/tldr/commit/38fa3557692f139247caf5b440ca5fd070cd41ea)
[Matthew Thompson](mailto:fortran@gmail.com) | Remove extra newline | 2017-12-15T23:13:20 | [5d1e62095eca](https://github.com/tldr-pages/tldr/commit/5d1e62095eca1eca8dc8a388f677adc515369a27)
[Matthew Thompson](mailto:fortran@gmail.com) | Add examples with 'dc -f' and 'dc -e' | 2017-12-15T23:12:48 | [5c0854ae0fd0](https://github.com/tldr-pages/tldr/commit/5c0854ae0fd0a905d1c8e0954e16da3a8da3a2d2)
[Matthew Thompson](mailto:matthew.thompson@nasa.gov) | Use a colon instead of comma | 2017-12-15T19:00:16 | [40547b829567](https://github.com/tldr-pages/tldr/commit/40547b8295674e6d482345022163cb28dd522c6c)
[Matthew Thompson](mailto:matthew.thompson@nasa.gov) | Fix spacing and commas. Me write English ungood | 2017-12-15T18:59:36 | [12e4418ffb37](https://github.com/tldr-pages/tldr/commit/12e4418ffb378a578ddf146cfb2371fb41f82f1d)
[Matthew Thompson](mailto:matthew.thompson@nasa.gov) | Remove trailing space | 2017-12-15T18:56:44 | [89cac75cff48](https://github.com/tldr-pages/tldr/commit/89cac75cff48a22446201a9267dcfcf621fe8f0e)
[Matthew Thompson](mailto:matthew.thompson@nasa.gov) | dc: add page | 2017-12-15T18:51:17 | [d12dce4c92c9](https://github.com/tldr-pages/tldr/commit/d12dce4c92c92f23fb1602aa98fb1154ffa25549)

