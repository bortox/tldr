---
author: ['Charles Tang', 'Agniva De Sarker', 'kxy', 'Forrest Desjardins', 'Axel Navarro', 'lord63', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Antoine Mazure', 'Te-Chi Liu', 'Ruben Vereecken']
date: 1623342380
title: "git clone"
description: "git clone, Clone an existing repository."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-clone>.

- Clone an existing repository:

```bash
git clone remote_repository_location
```

- Clone an existing repository into a specific directory:

```bash
git clone remote_repository_location path/to/directory
```

- Clone an existing repository and its submodules:

```bash
git clone --recursive remote_repository_location
```

- Clone a local repository:

```bash
git clone -l path/to/local/repository
```

- Clone quietly:

```bash
git clone -q remote_repository_location
```

- Clone an existing repository only fetching the 10 most recent commits on the default branch (useful to save time):

```bash
git clone --depth 10 remote_repository_location
```

- Clone an existing repository only fetching a specific branch:

```bash
git clone --branch name --single-branch remote_repository_location
```

- Clone an existing repository using a specific SSH command:

```bash
git clone --config core.sshCommand="ssh -i path/to/private_ssh_key" remote_repository_location
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | git-clone: add core.sshCommand example (#6109) | 2021-06-10T18:26:20 | [2f553aca0752](https://github.com/tldr-pages/tldr/commit/2f553aca0752a5ac0cb7697268dcbcd75c005d51)
[Antoine Mazure](mailto:12ab@gmx.fr) | git-clone: add clone single branch example (#4924) | 2020-11-03T12:48:52 | [d26f0c99076e](https://github.com/tldr-pages/tldr/commit/d26f0c99076e8b1d9f3e94f2606ffc743cfc3f75)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | git-clone: correct and reword examples (#3470) | 2019-10-27T12:07:00 | [13982a4fcba1](https://github.com/tldr-pages/tldr/commit/13982a4fcba1a9c3069c2e3e2ad30b2164ac1ad9)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | git-clone: wrapping depth in tokens | 2017-12-29T07:02:01 | [608b34a1cb0c](https://github.com/tldr-pages/tldr/commit/608b34a1cb0c63edbec05162e2c93df5b5526228)
[Forrest Desjardins](mailto:desjardinsfg@gmail.com) | git-clone: add `git clone --recursive` entry | 2017-12-28T09:10:06 | [2ed9d366b4c8](https://github.com/tldr-pages/tldr/commit/2ed9d366b4c82bcf5726c68913209fa0f9fb1fc7)
[Te-Chi Liu](mailto:liuderchi@gmail.com) | fixup: token string style (#1081) - use underscore rather than minus - use lower case rather than uppder case | 2016-09-21T17:35:46 | [5a54763c72d1](https://github.com/tldr-pages/tldr/commit/5a54763c72d1ed1b6eb5dbf195ee547527afc608)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Charles Tang](mailto:charlestang@foxmail.com) | git-clone with --depth argument when use git-clone with --depth argument will save your time remove following space of lines which [...] | 2015-12-25T12:19:32 | [3142f57a6112](https://github.com/tldr-pages/tldr/commit/3142f57a611203cc819cce775aac7664fb338f85)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[kxy](mailto:kyrwastaken@gmail.com) | split git commands | 2014-03-09T13:20:13 | [4d70294f065f](https://github.com/tldr-pages/tldr/commit/4d70294f065f8d6d9fd6c0add28968cb9ca725ff)

