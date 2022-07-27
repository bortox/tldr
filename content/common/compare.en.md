---
author: ['Valentin Vetter']
date: 1575054565
title: "compare, TLDR Pages"
description: "compare, View the difference between 2 images."
categories: "common"
---
> More information: <https://imagemagick.org/script/compare.php>.

- Compare 2 images:

```bash
compare image1.png image2.png diff.png
```

- Compare 2 images using a custom metric:

```bash
compare -verbose -metric PSNR image1.png image2.png diff.png
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Valentin Vetter](mailto:BeLi4L@users.noreply.github.com) | compare: add page (#3632) | 2019-11-29T20:09:25 | [c39ab84d4bdc](https://github.com/tldr-pages/tldr/commit/c39ab84d4bdc08c5ace2f05343bd5863ba3efdab)

