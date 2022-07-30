---
author: ['Waldir Pimenta', 'lucas schneider', 'Agniva De Sarker', 'Ricardo Corrie', 'Starbeamrainbowlabs', 'Marco Bonelli', 'Joel Huang', 'Seth Falco', 'Ruben Vereecken']
date: 1629050349
title: "git svn"
description: "git svn, Bidirectional operation between a Subversion repository and Git."
categories: "common"
---
> More information: <https://git-scm.com/docs/git-svn>.

- Clone an SVN repository:

```bash
git svn clone https://example.com/subversion_repo local_dir
```

- Clone an SVN repository starting at a given revision number:

```bash
git svn clone -r1234:HEAD https://svn.example.net/subversion/repo local_dir
```

- Update local clone from the remote SVN repository:

```bash
git svn rebase
```

- Fetch updates from the remote SVN repository without changing the Git HEAD:

```bash
git svn fetch
```

- Commit back to the SVN repository:

```bash
git svn dcommit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | git-svn: add example for making a shallow clone (#1136) | 2016-11-28T07:28:49 | [21e92ecc78fd](https://github.com/tldr-pages/tldr/commit/21e92ecc78fd486d3fb31882bbe49a915da55766)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | git-svn: fix page comments | 2016-09-20T09:27:09 | [1e9232a77dc8](https://github.com/tldr-pages/tldr/commit/1e9232a77dc80c6e1d7d7493fb904753017f92b8)
[Ricardo Corrie](mailto:rc@rcorrie.com) | Revision based on PR feedback | 2016-09-20T09:27:09 | [aaa8b61bd654](https://github.com/tldr-pages/tldr/commit/aaa8b61bd654e2a1726186d18ce09a202f08abef)
[Ricardo Corrie](mailto:rc@rcorrie.com) | git-svn: add `fetch` subcommand | 2016-09-20T09:27:09 | [3701b6973ffd](https://github.com/tldr-pages/tldr/commit/3701b6973ffd2f9935e7543106c49f0f5d8e92dc)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Joel Huang](mailto:joelhy@gmail.com) | git-svn: add page | 2016-01-05T09:40:34 | [0c8ec98b7562](https://github.com/tldr-pages/tldr/commit/0c8ec98b756201e3475c63ceaeafb8b58abf6e6e)

