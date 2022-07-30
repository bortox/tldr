---
author: ['Miguel Amigot', 'Igor Shubovych', 'André König', 'Eric Nielsen', 'Peter Tripp', 'xidui', 'Kiran Joshi', 'rprieto', 'alefir', 'Srinivasan R', 'Matt Terwilliger', 'Marco Bonelli', 'Ruben Vereecken']
date: 1615062554
title: "scp"
description: "scp, Secure copy."
categories: "common"
---
> Copy files between hosts using Secure Copy Protocol over SSH.

> More information: <https://man.openbsd.org/scp>.

- Copy a local file to a remote host:

```bash
scp path/to/local_file remote_host:path/to/remote_file
```

- Use a specific port when connecting to the remote host:

```bash
scp -P port path/to/local_file remote_host:path/to/remote_file
```

- Copy a file from a remote host to a local directory:

```bash
scp remote_host:path/to/remote_file path/to/local_directory
```

- Recursively copy the contents of a directory from a remote host to a local directory:

```bash
scp -r remote_host:path/to/remote_directory path/to/local_directory
```

- Copy a file between two remote hosts transferring through the local host:

```bash
scp -3 host1:path/to/remote_file host2:path/to/remote_directory
```

- Use a specific username when connecting to the remote host:

```bash
scp path/to/local_file remote_username@remote_host:path/to/remote_directory
```

- Use a specific ssh private key for authentication with the remote host:

```bash
scp -i ~/.ssh/private_key local_file remote_host:/path/remote_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Eric Nielsen](mailto:eric@amalgamar.com.br) | scp: fix -P example (#5343) The -P parameter comes first to use a specific port. | 2021-03-06T21:29:14 | [5e56c38d3780](https://github.com/tldr-pages/tldr/commit/5e56c38d3780d1cc550d59ab713fdf2b3e6470b4)
[Kiran Joshi](mailto:kiran.j88@gmail.com) | scp: add -P example (#5027) | 2020-12-17T11:16:17 | [365397c40b48](https://github.com/tldr-pages/tldr/commit/365397c40b4879b8168b76ec57b39275c626c9c5)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: improve consistency of the term "directory". This commit changes the term "folder" to "directory" in every instance where [...] | 2019-02-08T20:43:24 | [ac4094e0ad70](https://github.com/tldr-pages/tldr/commit/ac4094e0ad70a6be2163b06d24b53992b93aee4f)
[Matt Terwilliger](mailto:matt@terwilligers.com) | Recursive scp arguments reversed (#1321) * Recursive scp arguments reversed The command to "copy [...] on a remote host to a local [...] | 2017-04-18T15:07:46 | [11e745572e5c](https://github.com/tldr-pages/tldr/commit/11e745572e5c448e3837d7038965eecbbae64e1f)
[alefir](mailto:bob1nilly@gmail.com) | Change scp examples to match token syntax guidelines (#1203) | 2016-12-19T07:52:07 | [c81a256483fe](https://github.com/tldr-pages/tldr/commit/c81a256483fee8fbacea96bda8405e9ab03f0d7b)
[Miguel Amigot](mailto:miguel.amigot@gmail.com) | Wrong order of arguments in command | 2016-03-19T07:01:04 | [085b18642feb](https://github.com/tldr-pages/tldr/commit/085b18642feb3789f287c296a824ef232721f801)
[Peter Tripp](mailto:petertripp@gmail.com) | Rework scp. * No double examples * Replace IP address with hostname place holders. * change word use to avoid upload & download * [...] | 2016-01-16T11:21:23 | [eb973701a19c](https://github.com/tldr-pages/tldr/commit/eb973701a19cc26e1eb3b88723f2800886b4e844)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | scp: remove port example | 2015-12-26T10:43:33 | [384e17dcd6de](https://github.com/tldr-pages/tldr/commit/384e17dcd6de325344c3bfe39bccd204ac623d49)
[xidui](mailto:664984593@qq.com) | scp with ssh key | 2015-12-25T09:25:01 | [3e72760a45ee](https://github.com/tldr-pages/tldr/commit/3e72760a45eec44a9ed0148a37aff2fcebd27528)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Add extra newline between consecutive commands examples. These 6 files had multiple examples all separated by a single newline. While [...] | 2015-10-28T18:10:44 | [2097cf359d9b](https://github.com/tldr-pages/tldr/commit/2097cf359d9bc97448a1dceb5b9549426159ea69)
[André König](mailto:andre.koenig@gmail.com) | scp: specify port on host | 2014-05-26T11:02:20 | [45871b266286](https://github.com/tldr-pages/tldr/commit/45871b2662862abc6b647b8223464f507f2ead6c)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

