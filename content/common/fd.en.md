---
author: ['Schneider', 'sebastientinel', 'Tim Hwang', 'Lucas Gabriel Schneider', 'Juan Leñero', 'pxgamer', 'David Peter', 'sucrecacao', 'Muhammad Falak R Wani']
date: 1607742775
title: "fd"
description: "fd, An alternative to `find`."
categories: "common"
---
> Aims to be faster and easier to use than `find`.

> More information: <https://github.com/sharkdp/fd>.

- Recursively find files matching the given pattern in the current directory:

```bash
fd pattern
```

- Find files that begin with "foo":

```bash
fd '^foo'
```

- Find files with a specific extension:

```bash
fd --extension txt
```

- Find files in a specific directory:

```bash
fd pattern path/to/directory
```

- Include ignored and hidden files in the search:

```bash
fd --hidden --no-ignore pattern
```

- Execute a command on each search result returned:

```bash
fd pattern --exec command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Tim Hwang](mailto:timhwang21@users.noreply.github.com) | fd: add --exec (#5019) | 2020-12-12T04:12:55 | [f6748fd0902b](https://github.com/tldr-pages/tldr/commit/f6748fd0902b86d2249059f74e52c3331662c70c)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[sucrecacao](mailto:55893070+sucrecacao@users.noreply.github.com) | fd: specify that the search is recursive (#4371) | 2020-10-05T14:11:41 | [4f73077e6853](https://github.com/tldr-pages/tldr/commit/4f73077e6853093e91b12d46acd5317048a97cbf)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | find: update description Co-Authored-By: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2019-10-13T05:28:04 | [3358db816e10](https://github.com/tldr-pages/tldr/commit/3358db816e106af17c60fa3854709e9b8fdcdc5a)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | fd: fix typo Co-Authored-By: Andrik Albuquerque <andrik.albuquerque@gmail.com> | 2019-10-13T05:28:04 | [f108b4dc5cad](https://github.com/tldr-pages/tldr/commit/f108b4dc5cad9c7a3e352f3f2649d9dbb295aa22)
[Schneider](mailto:lucas.schneider@sap.com) | multiple pages: rephrase without adjectives | 2019-10-13T05:28:04 | [42152ed45923](https://github.com/tldr-pages/tldr/commit/42152ed459230c2b244529f0c5990335e0057c6c)
[pxgamer](mailto:owzie123@gmail.com) | fd: add link to homepage | 2019-06-07T23:58:59 | [1640120fd3fc](https://github.com/tldr-pages/tldr/commit/1640120fd3fcac8a8afbc4fd253fcd1084069d82)
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | fd: use backticks for referencing commands (#2705) | 2019-01-12T16:09:05 | [97bfe0a76e53](https://github.com/tldr-pages/tldr/commit/97bfe0a76e53c190e691c6bb0ef058b27ce553e8)
[David Peter](mailto:sharkdp@users.noreply.github.com) | fd: minor adjustments (#2700) | 2019-01-11T11:06:58 | [653377d52166](https://github.com/tldr-pages/tldr/commit/653377d521660a7f4175be391fbf48a6385541b6)
[Juan Leñero](mailto:juanjo.lenero@gmail.com) | dir -> directory | 2017-10-23T04:40:39 | [ff4ea8adc60b](https://github.com/tldr-pages/tldr/commit/ff4ea8adc60b554078acccd1b6b4c31739ba9829)
[Juan Leñero](mailto:juanjo.lenero@gmail.com) | Use tokens for client highlighting. | 2017-10-21T04:24:07 | [8708fcbee337](https://github.com/tldr-pages/tldr/commit/8708fcbee3373896ebe411259ee93dc8d11a46ea)
[Juan Leñero](mailto:juanjo.lenero@gmail.com) | fd: add page | 2017-10-21T04:12:59 | [0c4edde86b3a](https://github.com/tldr-pages/tldr/commit/0c4edde86b3a3e58fc34280543dcd7235e17e5de)

