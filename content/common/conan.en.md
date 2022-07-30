---
author: ['stellarstriker', 'bl-ue', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1631521281
title: "conan"
description: "conan, The open source, decentralized and cross-platform package manager to create and share all your native binaries."
categories: "common"
---
> Some subcommands such as `conan frogarian` have their own usage documentation.

> More information: <https://conan.io/>.

- Install packages based on `conanfile.txt`:

```bash
conan install .
```

- Install packages and create configuration files for a specific generator:

```bash
conan install -g generator
```

- Install packages, building from source:

```bash
conan install . --build
```

- Search for locally installed packages:

```bash
conan search package
```

- Search for remote packages:

```bash
conan search package -r remote
```

- List remotes:

```bash
conan remote list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[stellarstriker](mailto:37715255+stellarstriker@users.noreply.github.com) | Fix invalid command (#6260) | 2021-07-25T21:08:27 | [af41cf8d9e33](https://github.com/tldr-pages/tldr/commit/af41cf8d9e33ef117cb2ef7836c189c3d7d20f6e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | conan, php-coveralls: fix typos (#5253) | 2021-02-07T04:48:45 | [a810ca72d7aa](https://github.com/tldr-pages/tldr/commit/a810ca72d7aa01cd5b9093d4b208b23c5b2982e0)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | conan: add page (#5008) | 2020-12-12T19:06:49 | [cc8246f3aaa4](https://github.com/tldr-pages/tldr/commit/cc8246f3aaa46eee525565c7d4158d3c59a345ca)

