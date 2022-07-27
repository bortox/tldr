---
author: ['marchersimon']
date: 1658919612
title: "cargo add, TLDR Pages"
description: "cargo add, Add dependencies to a Rust project's `Cargo.toml` file."
categories: "common"
---
> More information: <https://doc.rust-lang.org/cargo/commands/cargo-add.html>.

- Add the latest version of a dependency to the current project:

```bash
cargo add dependency
```

- Add a specific version of a dependency:

```bash
cargo add dependency@version
```

- Add a dependency and enable one or more specific features:

```bash
cargo add dependency --features feature_1,feature_2
```

- Add an optional dependency, which then gets exposed as a feature of the crate:

```bash
cargo add dependency --optional
```

- Add a local crate as a dependency:

```bash
cargo add --path path/to/crate
```

- Add a development or build dependency:

```bash
cargo add dependency --dev|build
```

- Add a dependency with all default features disabled:

```bash
cargo add dependency --no-default-features
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cargo-add: add page (#8246) | 2022-07-27T13:00:12 | [42e2ab19f524](https://github.com/tldr-pages/tldr/commit/42e2ab19f5249c4aaa35ca89cf1ed19ffd37cc51)

