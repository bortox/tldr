---
author: ['João Farias', 'Ethan Kinnear', 'Emily Grace Seville', 'Marco Bonelli', 'Niklas Heer', 'Galdin Raphael', 'Larry Lu', 'Florian Bruhin', 'Seth Falco', 'Starbeamrainbowlabs']
date: 1657742150
title: "code, TLDR Pages"
description: "code, Cross platform and extensible code editor."
categories: "common"
---
> More information: <https://github.com/microsoft/vscode>.

- Start Visual Studio Code:

```bash
code
```

- Open specific files/directories:

```bash
code path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Compare two specific files:

```bash
code --diff path/to/file1 path/to/file2
```

- Open specific files/directories in a new window:

```bash
code --new-window path/to/file_or_directory1 path/to/file_or_directory2 ...
```

- Install/uninstall a specific extension:

```bash
code --install|uninstall-extension publisher.extension
```

- Print installed extensions:

```bash
code --list-extensions
```

- Print installed extensions with their versions:

```bash
code --list-extensions --show-versions
```

- Start the editor as a superuser (root) while storing user data in a specific directory:

```bash
sudo code --user-data-dir path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ethan Kinnear](mailto:contact@superatomic.dev) | code: fix typo in --user-data-dir example (#8207) | 2022-07-13T21:55:50 | [3d8df897be59](https://github.com/tldr-pages/tldr/commit/3d8df897be59cce2c58b97b2d3781076063e1fa2)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | code: refresh page (#8017) * Refresh page: - reorder examples - better descriptions - fix placeholder samples * Replace `editor` with [...] | 2022-04-16T04:42:11 | [34fa69097933](https://github.com/tldr-pages/tldr/commit/34fa690979332f55c09714d9c3ae99f778561f98)
[Florian Bruhin](mailto:me@the-compiler.org) | code: add --new-window example (#7717) | 2022-01-27T18:12:15 | [8a277402e8fd](https://github.com/tldr-pages/tldr/commit/8a277402e8fd4ecf76e6e88fec3abedd6616d701)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[João Farias](mailto:jgfarias42@gmail.com) | Adding entry for how to run VS Code with sudo permissions - EN and PT-BR (#4119) | 2020-06-20T17:27:01 | [4ed86c38da46](https://github.com/tldr-pages/tldr/commit/4ed86c38da460d58665f35b134d19c349fa166d6)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: improve consistency of the term "directory". This commit changes the term "folder" to "directory" in every instance where [...] | 2019-02-08T20:43:24 | [ac4094e0ad70](https://github.com/tldr-pages/tldr/commit/ac4094e0ad70a6be2163b06d24b53992b93aee4f)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Larry Lu](mailto:pudding850806@gmail.com) | code: add compare two files example (#2631) * code: add compare two files example | 2018-12-03T16:18:25 | [5cf150a17d0c](https://github.com/tldr-pages/tldr/commit/5cf150a17d0c1ff026a53235aa9c9c543351e470)
[Niklas Heer](mailto:me@nheer.io) | code: add --reuse-window example (#1804) | 2017-12-18T11:26:49 | [8508e6a4bbfe](https://github.com/tldr-pages/tldr/commit/8508e6a4bbfe06a3296a6b64d1cfe39d8cac2804)
[Galdin Raphael](mailto:gldraphael@users.noreply.github.com) | code: add page (#1557) | 2017-10-24T18:11:53 | [1b930944d479](https://github.com/tldr-pages/tldr/commit/1b930944d479aa2392d57c985c1194819aff3e11)

