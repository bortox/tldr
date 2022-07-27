---
author: ['Lukáš Zapletal', 'bl-ue', 'Ryan Geary', 'Émile Nadeau', 'pydo', 'git-em', 'CleanMachine1', 'Axel Navarro', 'marchersimon']
date: 1647070865
title: "nmcli, TLDR Pages"
description: "nmcli, A command-line tool for controlling NetworkManager."
categories: "linux"
---
> Some subcommands such as `nmcli monitor` have their own usage documentation.

> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Run an `nmcli` subcommand:

```bash
nmcli agent|connection|device|general|help|monitor|networking|radio command_options
```

- Display the current version of NetworkManager:

```bash
nmcli --version
```

- Display help:

```bash
nmcli --help
```

- Display help for a subcommand:

```bash
nmcli subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | nmcli, nmcli-monitor: update link (#7862) | 2022-03-12T08:41:05 | [452d56612f25](https://github.com/tldr-pages/tldr/commit/452d56612f25e6ad801e9689dc2e47e00eb10fec)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | nmcli: refresh (#6203) | 2021-07-11T21:40:19 | [2b871bedec84](https://github.com/tldr-pages/tldr/commit/2b871bedec845d2f70417bcbb772992832aec805)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Axel Navarro](mailto:navarroaxel@gmail.com) | nmcli: add more information link (#5198) | 2021-01-30T22:05:59 | [23d7996775e1](https://github.com/tldr-pages/tldr/commit/23d7996775e12580a5af45034372cc86c055bf24)
[Lukáš Zapletal](mailto:lzap@redhat.com) | nmcli: add more server examples (#3816) | 2020-03-06T18:10:05 | [e54c56236138](https://github.com/tldr-pages/tldr/commit/e54c562361387aac7856baf59111961c3c0e2999)
[Ryan Geary](mailto:rtgnj42@gmail.com) | nmcli: add password flag to command (#3256) | 2019-09-02T17:22:40 | [d62b78592725](https://github.com/tldr-pages/tldr/commit/d62b7859272580fd9fe24daf024b324166206453)
[Émile Nadeau](mailto:nadeau.emile@gmail.com) | nmcli: connecting wifi network examples (#2215) | 2018-07-29T00:31:35 | [13eed8652733](https://github.com/tldr-pages/tldr/commit/13eed8652733c12a15826690bfff01bb34d783ba)
[pydo](mailto:pydo@fastmail.com) | nmcli: add page (#1547) | 2017-10-16T13:41:31 | [d7a1ab25503e](https://github.com/tldr-pages/tldr/commit/d7a1ab25503ed0f372aea4f70c024ce4fb5f967b)

