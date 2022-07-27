---
author: ['Alvise Trevisan', 'Axel Navarro']
date: 1604243162
title: "cargo build, TLDR Pages"
description: "cargo build, Compile a local package and all of its dependencies."
categories: "common"
---
> More information: <https://doc.rust-lang.org/cargo/commands/cargo-build.html>.

- Build the package or packages defined by the `Cargo.toml` manifest file in the local path:

```bash
cargo build
```

- Build artifacts in release mode, with optimizations:

```bash
cargo build --release
```

- Require that `Cargo.lock` is up to date:

```bash
cargo build --locked
```

- Build all packages in the workspace:

```bash
cargo build --workspace
```

- Build a specific package:

```bash
cargo build --package package
```

- Build only the specified binary:

```bash
cargo build --bin name
```

- Build only the specified test target:

```bash
cargo build --test testname
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alvise Trevisan](mailto:a.trevisan@enpicom.com) | cargo-build: fix --bin subcommand (#4921) | 2020-11-01T16:06:02 | [b804c909d3b9](https://github.com/tldr-pages/tldr/commit/b804c909d3b986837b36eabc52583bfccb3534b0)
[Axel Navarro](mailto:navarroaxel@gmail.com) | cargo-build: add page (#4302) | 2020-09-08T18:19:03 | [43c136ffe7af](https://github.com/tldr-pages/tldr/commit/43c136ffe7afa6901eaf32ac0a958b652b1bd6b3)

