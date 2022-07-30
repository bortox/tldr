---
author: ['Starbeamrainbowlabs', 'Marco Bonelli']
date: 1580730823
title: "f3probe"
description: "f3probe, Probe a block device (e.g. a flash drive or a microSD card) for counterfeit flash memory."
categories: "common"
---
> See also `f3read`, `f3write`, `f3fix`.

> More information: <https://github.com/AltraMayor/f3>.

- Probe a block device:

```bash
sudo f3probe path/to/block_device
```

- Use the minimum about of RAM possible:

```bash
sudo f3probe --min-memory path/to/block_device
```

- Time disk operations:

```bash
sudo f3probe --time-ops path/to/block_device
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | f3probe: add sudo | 2020-02-03T12:53:43 | [34a4dfb6662e](https://github.com/tldr-pages/tldr/commit/34a4dfb6662e70364a8b3d87140909e6783d2dc0)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | f3probe: add see also | 2020-02-03T12:53:43 | [1bef364ccbb6](https://github.com/tldr-pages/tldr/commit/1bef364ccbb62e98b3ce7caa2e4e3be6432de0aa)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | f3probe: add page (#3039) | 2019-05-19T18:38:28 | [8be8ce83804c](https://github.com/tldr-pages/tldr/commit/8be8ce83804cb86b1ce3c88efdb73a63e6e833bc)

