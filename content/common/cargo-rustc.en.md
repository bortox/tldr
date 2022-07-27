---
author: ['Axel Navarro']
date: 1600793778
title: "cargo rustc, TLDR Pages"
description: "cargo rustc, Compile a Rust package, and pass extra options to the compiler."
categories: "common"
---
> More information: <https://doc.rust-lang.org/cargo/commands/cargo-rustc.html>.

- Build the package or packages defined by the `Cargo.toml` manifest file in the current working directory:

```bash
cargo rustc
```

- Build artifacts in release mode, with optimizations:

```bash
cargo rustc --release
```

- Compile with architecture-specific optimizations for the current CPU:

```bash
cargo rustc --release -- -C target-cpu=native
```

- Compile with speed optimization:

```bash
cargo rustc -- -C opt-level 1|2|3
```

- Compile with [s]ize optimization (`z` also turns off loop vectorization):

```bash
cargo rustc -- -C opt-level s|z
```

- Check if your package uses unsafe code:

```bash
cargo rustc --lib -- -D unsafe-code
```

- Build a specific package:

```bash
cargo rustc --package package
```

- Build only the specified binary:

```bash
cargo --bin name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | cargo-rustc: add page (#4336) | 2020-09-22T18:56:18 | [25effa9da656](https://github.com/tldr-pages/tldr/commit/25effa9da656b3592075052041bf0c4b6c4edf7f)

