---
author: ['Nicolas Kosinski', 'Axel Navarro']
date: 1631473628
title: "cargo clippy, TLDR Pages"
description: "cargo clippy, A collection of lints to catch common mistakes and improve your Rust code."
categories: "common"
---
> More information: <https://github.com/rust-lang/rust-clippy>.

- Run checks over the code in the current directory:

```bash
cargo clippy
```

- Require that `Cargo.lock` is up to date:

```bash
cargo clippy --locked
```

- Run checks on all packages in the workspace:

```bash
cargo clippy --workspace
```

- Run checks for a package:

```bash
cargo clippy --package package
```

- Treat warnings as errors:

```bash
cargo clippy -- --deny warnings
```

- Run checks and ignore warnings:

```bash
cargo clippy -- --allow warnings
```

- Apply Clippy suggestions automatically:

```bash
cargo clippy --fix
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@users.noreply.github.com) | cargo-clippy: use long arguments (#6503) | 2021-09-12T21:07:08 | [8af1bb114597](https://github.com/tldr-pages/tldr/commit/8af1bb114597c04705009f608ab512fe8a66425e)
[Axel Navarro](mailto:navarroaxel@gmail.com) | cargo-clippy: add page (#4316) | 2020-09-12T22:06:27 | [35e14c57c505](https://github.com/tldr-pages/tldr/commit/35e14c57c505eb3a0a70da5bff81a91ee8dc826e)

