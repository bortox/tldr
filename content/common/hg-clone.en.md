---
author: ['pxgamer', 'Lucas Gabriel Schneider', 'Agniva De Sarker', 'Marco Bonelli']
date: 1612112718
title: "hg clone"
description: "hg clone, Create a copy of an existing repository in a new directory."
categories: "common"
---
> More information: <https://www.mercurial-scm.org/doc/hg.1.html#clone>.

- Clone a repository to a specified directory:

```bash
hg clone remote_repository_source destination_path
```

- Clone a repository to the head of a specific branch, ignoring later commits:

```bash
hg clone --branch branch remote_repository_source
```

- Clone a repository with only the `.hg` directory, without checking out files:

```bash
hg clone --noupdate remote_repository_source
```

- Clone a repository to a specific revision, tag or branch, keeping the entire history:

```bash
hg clone --updaterev revision remote_repository_source
```

- Clone a repository up to a specific revision without any newer history:

```bash
hg clone --rev revision remote_repository_source
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | hg-clone: add link to homepage | 2019-03-24T00:27:35 | [814c761496e2](https://github.com/tldr-pages/tldr/commit/814c761496e29b58383bb3555b4bf378f4fa2125)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Clarify .hg directory | 2017-12-18T13:17:57 | [b67ac7a2df07](https://github.com/tldr-pages/tldr/commit/b67ac7a2df07ef71b5efa2e9c1c3f97b3ff10dba)
[pxgamer](mailto:owzie123@gmail.com) | Applied changes to the hg-clone page | 2017-12-18T13:11:06 | [f0d04fc6460f](https://github.com/tldr-pages/tldr/commit/f0d04fc6460f0a4ea3d9cb3add38179b5e2ffa40)
[pxgamer](mailto:owzie123@gmail.com) | hg-clone: add page | 2017-12-15T11:28:53 | [5e4f41603c46](https://github.com/tldr-pages/tldr/commit/5e4f41603c465bc87b9887977041c5e454fccfc1)

