---
author: ['Russ Edwards', 'Agniva De Sarker', 'Starbeamrainbowlabs', 'Marco Bonelli']
date: 1560331567
title: "hyperfine"
description: "hyperfine, A command-line benchmarking tool."
categories: "common"
---
> More information: <https://github.com/sharkdp/hyperfine/>.

- Run a basic benchmark, performing at least 10 runs:

```bash
hyperfine 'make'
```

- Run a comparative benchmark:

```bash
hyperfine 'make target1' 'make target2'
```

- Change minimum number of benchmarking runs:

```bash
hyperfine --min-runs 7 'make'
```

- Perform benchmark with warmup:

```bash
hyperfine --warmup 5 'make'
```

- Run a command before each benchmark run (to clear caches, etc.):

```bash
hyperfine --prepare 'make clean' 'make'
```

- Run a benchmark where a single parameter changes for each run:

```bash
hyperfine --prepare 'make clean' --parameter-scan num_threads 1 10 'make -j {num_threads}'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | hyperfine: fix typo (#3104) | 2019-06-12T11:26:07 | [2191ed070dd5](https://github.com/tldr-pages/tldr/commit/2191ed070dd57fc8df8dddc4784deec4e1dee063)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | hyperfine: update examples (#2395) | 2018-10-05T15:26:21 | [977b4c60dca8](https://github.com/tldr-pages/tldr/commit/977b4c60dca8b8dcaeecc4ca0502da22883c938b)
[Russ Edwards](mailto:redwards@digitellinc.com) | hyperfine: update basic example to include the minimum number of runs (#2385) Merged. Thanks | 2018-10-04T21:03:37 | [242c481d7d2d](https://github.com/tldr-pages/tldr/commit/242c481d7d2ddc207a1363ba4d4201973bf409fc)
[Russ Edwards](mailto:redwards@digitellinc.com) | hyperfine: add page (#2368) | 2018-10-02T23:02:57 | [5e0e5ddd442d](https://github.com/tldr-pages/tldr/commit/5e0e5ddd442d79d76b3e625830a7747e48dfdd8c)

