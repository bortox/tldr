---
author: ['Waldir Pimenta', 'lucas schneider', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Eliot Sykes', 'Jibran Kalia']
date: 1610111394
title: "git clean"
description: "git clean, Remove untracked files from the working tree."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-clean>.

- Delete files that are not tracked by Git:

```bash
git clean
```

- Interactively delete files that are not tracked by Git:

```bash
git clean -i
```

- Show what files would be deleted without actually deleting them:

```bash
git clean --dry-run
```

- Forcefully delete files that are not tracked by Git:

```bash
git clean -f
```

- Forcefully delete directories that are not tracked by Git:

```bash
git clean -fd
```

- Delete untracked files, including ignored files in `.gitignore` and `.git/info/exclude`:

```bash
git clean -x
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Jibran Kalia](mailto:jibran.kalia@gmail.com) | git-clean: add -fd option | 2018-07-09T18:51:38 | [30ad96e27afb](https://github.com/tldr-pages/tldr/commit/30ad96e27afb73152d1325b33f72e79960d9604a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-clean: fix verb tense | 2017-04-20T21:03:36 | [9475cd358990](https://github.com/tldr-pages/tldr/commit/9475cd358990f7fba389b6b75f87e362b746b7f7)
[Eliot Sykes](mailto:eliotsykes@gmail.com) | Typo fix. Simplify git exclude path. | 2017-04-20T21:03:36 | [4d80ebdc16bd](https://github.com/tldr-pages/tldr/commit/4d80ebdc16bdc97a88ffe1b186811e2e553c4843)
[Eliot Sykes](mailto:eliotsykes@gmail.com) | Add git clean -f, -x options | 2017-04-20T21:03:36 | [100320e3a669](https://github.com/tldr-pages/tldr/commit/100320e3a6698108b036095489a58e7bff16af44)
[Eliot Sykes](mailto:eliotsykes@gmail.com) | git-clean: add page | 2017-04-20T21:03:36 | [18b9f11a299b](https://github.com/tldr-pages/tldr/commit/18b9f11a299bcc32a6df3d44fb80a83baf6d4a04)

