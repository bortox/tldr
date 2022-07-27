---
author: ['Axel Navarro', 'Jake Vossen']
date: 1634654872
title: "cargo test, TLDR Pages"
description: "cargo test, Execute the unit and integration tests of a Rust package."
categories: "common"
---
> More information: <https://doc.rust-lang.org/cargo/commands/cargo-test.html>.

- Only run tests containing a specific string in their names:

```bash
cargo test testname
```

- Set the number of simultaneous running test cases:

```bash
cargo test -- --test-threads=count
```

- Require that `Cargo.lock` is up to date:

```bash
cargo test --locked
```

- Test artifacts in release mode, with optimizations:

```bash
cargo test --release
```

- Test all packages in the workspace:

```bash
cargo test --workspace
```

- Run tests for a package:

```bash
cargo test --package package
```

- Run tests without hiding output from test executions:

```bash
cargo test -- --nocapture
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jake Vossen](mailto:jake@vossen.dev) | cargo-test: add --nocapture example (#7098) | 2021-10-19T16:47:52 | [1ea448486765](https://github.com/tldr-pages/tldr/commit/1ea448486765639ae0db543b05c22523eb158acc)
[Axel Navarro](mailto:navarroaxel@gmail.com) | cargo-build: add page (#4302) | 2020-09-08T18:19:03 | [43c136ffe7af](https://github.com/tldr-pages/tldr/commit/43c136ffe7afa6901eaf32ac0a958b652b1bd6b3)
[Axel Navarro](mailto:navarroaxel@gmail.com) | cargo-test: add page (#4268) | 2020-08-30T06:00:03 | [9931dfbd1ecf](https://github.com/tldr-pages/tldr/commit/9931dfbd1ecf4bb5b86c04c0b463ea2a18108b68)

