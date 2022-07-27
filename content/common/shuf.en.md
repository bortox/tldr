---
author: ['anakimluke', 'Felix Yan', 'Dario Vladović', 'marchersimon']
date: 1621537658
title: "shuf, TLDR Pages"
description: "shuf, Generate random permutations."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/shuf>.

- Randomize the order of lines in a file and output the result:

```bash
shuf filename
```

- Only output the first 5 entries of the result:

```bash
shuf --head-count=5 filename
```

- Write the output to another file:

```bash
shuf filename --output=output_filename
```

- Generate 3 random numbers in the range 1-10 (inclusive):

```bash
shuf --head-count=3 --input-range=1-10 --repeat
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[anakimluke](mailto:anakimluke@users.noreply.github.com) | shuf: expand short options to long ones (#6001) | 2021-05-20T21:07:38 | [23b9d8fe69b6](https://github.com/tldr-pages/tldr/commit/23b9d8fe69b66becb6cfc604e8584eac10da1c0f)
[anakimluke](mailto:anakimluke@users.noreply.github.com) | shuf: improve usage example and its description (#5992) | 2021-05-20T16:50:45 | [5d3be85e4d73](https://github.com/tldr-pages/tldr/commit/5d3be85e4d73cc207d543215f1f00c9ae1d817b0)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | shuf: add link (#5591) | 2021-03-30T15:56:33 | [be246d97b032](https://github.com/tldr-pages/tldr/commit/be246d97b032eafe6562241ce6bac122b3ae6f56)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

