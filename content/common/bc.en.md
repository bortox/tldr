---
author: ['Emily Grace Seville', 'Ruben Vereecken', 'Igor Shubovych', 'kalebo', 'marchersimon']
date: 1642831209
title: "bc, TLDR Pages"
description: "bc, An arbitrary precision calculator language."
categories: "common"
---
> See also: `dc`.

> More information: <https://manned.org/man/bc.1>.

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
echo '5 / 3' | bc
```

- Execute a script:

```bash
bc path/to/script.bc
```

- Calculate an expression with the specified scale:

```bash
echo 'scale = 10; 5 / 3' | bc
```

- Calculate a sine/cosine/arctangent/natural logarithm/exponential function using `mathlib`:

```bash
echo 's|c|a|l|e(1)' | bc --mathlib
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | bc, dc: refresh page (#7670) | 2022-01-22T07:00:09 | [47445dd78609](https://github.com/tldr-pages/tldr/commit/47445dd7860917026b4df1845f4c54a0f3d6ab94)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | bc: add link | 2021-04-18T16:33:27 | [2c7348ccdd6b](https://github.com/tldr-pages/tldr/commit/2c7348ccdd6bc47e877d760a180c8cd685d9a4e8)
[kalebo](mailto:kaleb.olson@gmail.com) | Changing wording in scale example * 'decimal places' used instead of 'precision' * Implicit example of using scale | 2017-02-26T05:56:11 | [262561ca7807](https://github.com/tldr-pages/tldr/commit/262561ca7807bcf0e070568710be3f0da8b67f0b)
[kalebo](mailto:kaleb.olson@gmail.com) | simplification * merged lines about interactive mode and mathlib | 2017-02-26T05:56:11 | [e3f1d3377fa3](https://github.com/tldr-pages/tldr/commit/e3f1d3377fa318fd79f47de67c8ce87381e96893)
[kalebo](mailto:kaleb.olson@gmail.com) | Added a line about interactive usage with mathlib Usually `bc` isn't very useful if it doesn't return have floating point number where [...] | 2017-02-26T05:56:11 | [1b5152e58f82](https://github.com/tldr-pages/tldr/commit/1b5152e58f821e4c45730b9e8201cbcecf73f579)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | bc: add page | 2015-12-14T12:04:29 | [8335e8447640](https://github.com/tldr-pages/tldr/commit/8335e8447640500dfee823c01d054331f46900d2)

