---
author: ['lucas schneider', 'Agniva De Sarker', 'Forrest Desjardins', 'Zak Remer', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Te-Chi Liu']
date: 1610111394
title: "git submodule"
description: "git submodule, Inspects, updates and manages submodules."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-submodule>.

- Install a repository's specified submodules:

```bash
git submodule update --init --recursive
```

- Add a Git repository as a submodule:

```bash
git submodule add repository_url
```

- Add a Git repository as a submodule at the specified directory:

```bash
git submodule add repository_url path/to/directory
```

- Update every submodule to its latest commit:

```bash
git submodule foreach git pull
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | git-submodule: use the standard directory convention | 2017-12-29T08:47:25 | [f8795d0c0129](https://github.com/tldr-pages/tldr/commit/f8795d0c0129f1a2e5b2f073cdacc8f8642ef188)
[Forrest Desjardins](mailto:desjardinsfg@gmail.com) | git-submodule: add `git submodule add` with path example | 2017-12-29T08:26:52 | [a668fe1db345](https://github.com/tldr-pages/tldr/commit/a668fe1db3456456074391ca9bf6af46aa657f32)
[Te-Chi Liu](mailto:liuderchi@gmail.com) | fixup: token string style (#1081) - use underscore rather than minus - use lower case rather than uppder case | 2016-09-21T17:35:46 | [5a54763c72d1](https://github.com/tldr-pages/tldr/commit/5a54763c72d1ed1b6eb5dbf195ee547527afc608)
[Zak Remer](mailto:zak.remer@gmail.com) | git-submodule: Add tldr page for the git-submodule command. Update git-submodule to pass linter requirements. | 2016-03-29T23:06:55 | [b184ceca66df](https://github.com/tldr-pages/tldr/commit/b184ceca66df0bd5f1820d556a1400ecd8c455eb)

