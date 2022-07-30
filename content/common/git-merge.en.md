---
author: ['Dillon Flamand', 'Danny Kim', 'Borek Bernard', 'lord63', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Te-Chi Liu', 'kxy', 'Ruben Vereecken']
date: 1576614916
title: "git merge"
description: "git merge, Merge branches."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-merge>.

- Merge a branch into your current branch:

```bash
git merge branch_name
```

- Edit the merge message:

```bash
git merge -e branch_name
```

- Merge a branch and create a merge commit:

```bash
git merge --no-ff branch_name
```

- Abort a merge in case of conflicts:

```bash
git merge --abort
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Danny Kim](mailto:DanielKim1@users.noreply.github.com) | git-merge: reword git merge description (#3662) | 2019-12-17T21:35:16 | [0e4edc1afc6d](https://github.com/tldr-pages/tldr/commit/0e4edc1afc6d28ed02bb320aaba698a2ba0dfba9)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Borek Bernard](mailto:borekb@gmail.com) | git-merge: --abort mentions that it's for situations with conflicts | 2018-07-19T10:15:22 | [9225a7b2d596](https://github.com/tldr-pages/tldr/commit/9225a7b2d5966d50e5eff502e167229396c0ca01)
[Borek Bernard](mailto:borekb@gmail.com) | git-merge: add --abort | 2018-07-19T10:15:22 | [bade4c7c0398](https://github.com/tldr-pages/tldr/commit/bade4c7c0398d2088e84953332761a440d9ffbfc)
[Dillon Flamand](mailto:dflamand@users.noreply.github.com) | git-merge: add --no-ff example Include an example and brief description of the --no-ff option | 2018-04-04T15:25:22 | [4bd7a1da174d](https://github.com/tldr-pages/tldr/commit/4bd7a1da174d940628c622cdbc5191b8af3e06ab)
[Te-Chi Liu](mailto:liuderchi@gmail.com) | fixup: token string style (#1081) - use underscore rather than minus - use lower case rather than uppder case | 2016-09-21T17:35:46 | [5a54763c72d1](https://github.com/tldr-pages/tldr/commit/5a54763c72d1ed1b6eb5dbf195ee547527afc608)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[kxy](mailto:kyrwastaken@gmail.com) | split git commands | 2014-03-09T13:20:13 | [4d70294f065f](https://github.com/tldr-pages/tldr/commit/4d70294f065f8d6d9fd6c0add28968cb9ca725ff)

