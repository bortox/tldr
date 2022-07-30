---
author: ['James', 'Schneider', 'Nicolas Kosinski', 'Daniel Campoverde [alx741]', 'bjorn3', 'Marco Bonelli', 'marchersimon']
date: 1631521281
title: "cargo"
description: "cargo, Manage Rust projects and their module dependencies (crates)."
categories: "common"
---
> Some subcommands such as `cargo build` have their own usage documentation.

> More information: <https://crates.io/>.

- Search for crates:

```bash
cargo search search_string
```

- Install a crate:

```bash
cargo install crate_name
```

- List installed crates:

```bash
cargo install --list
```

- Create a new binary or library Rust project in the current directory:

```bash
cargo init --bin|lib
```

- Create a new binary or library Rust project in the specified directory:

```bash
cargo new path/to/directory --bin|lib
```

- Build the Rust project in the current directory:

```bash
cargo build
```

- Build using a specific number of threads (default is the number of CPU cores):

```bash
cargo build --jobs number_of_threads
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Nicolas Kosinski](mailto:nicokosi@users.noreply.github.com) | cargo: use long options everywhere (#6502) | 2021-09-11T09:53:04 | [d3460ef8f103](https://github.com/tldr-pages/tldr/commit/d3460ef8f103a660f6f6765265b838b919342f1a)
[bjorn3](mailto:bjorn3@users.noreply.github.com) | cargo: Reword cargo build -j example | 2019-10-27T15:49:59 | [1eba2d951394](https://github.com/tldr-pages/tldr/commit/1eba2d9513941f12719ef517ea4ee102fd8608ba)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | cargo.md: add homepage | 2019-05-04T15:48:27 | [9baf6a7ba087](https://github.com/tldr-pages/tldr/commit/9baf6a7ba087fd8eba4a9d0e5d58e8922d08274a)
[James](mailto:jamesmmizen@gmail.com) | cargo: add cargo new (#2704) | 2019-01-13T05:00:16 | [6790ef5383e6](https://github.com/tldr-pages/tldr/commit/6790ef5383e6d983f1a4fc94dd123aee8ec6a87a)
[Daniel Campoverde [alx741]](mailto:alx741@riseup.net) | cargo: add page | 2016-05-05T03:39:32 | [05d68a00560e](https://github.com/tldr-pages/tldr/commit/05d68a00560e19bfb2cf41f64ce13e27ac5df0bb)

