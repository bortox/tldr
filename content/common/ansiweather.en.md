---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider', 'Schneider', 'David']
date: 1559564381
title: "ansiweather, TLDR Pages"
description: "ansiweather, A shell script for displaying the current weather conditions in your terminal."
categories: "common"
---
> More information: <https://github.com/fcambus/ansiweather>.

- Display a forecast using metric units for the next five days for Rzeszow, Poland:

```bash
ansiweather -u metric -f 5 -l Rzeszow,PL
```

- Display a forecast showing symbols and daylight data for your current location:

```bash
ansiweather -s true -d true
```

- Display a forecast showing wind and humidity data for your current location:

```bash
ansiweather -w true -h true
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | Fixed linting error | 2019-04-11T09:49:15 | [2c7f152eff6d](https://github.com/tldr-pages/tldr/commit/2c7f152eff6d8c24e131e661c40881f29769fde5)
[Schneider](mailto:lucas.schneider@sap.com) | ansiweather.md add homepage | 2019-04-11T09:49:15 | [605c77bf5059](https://github.com/tldr-pages/tldr/commit/605c77bf5059e2981e122ca31532207ecbf7c863)
[David](mailto:david.bialik@gmail.com) | ansiweather: add page (#2539) | 2018-11-05T22:58:01 | [c0e9b908e420](https://github.com/tldr-pages/tldr/commit/c0e9b908e4209b16cdd0c19fac9335e1d01baa72)

