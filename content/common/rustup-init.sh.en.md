---
author: ['marchersimon']
date: 1659026066
title: "rustup-init.sh, TLDR Pages"
description: "rustup-init.sh, Script to install `rustup` and the Rust toolchain."
categories: "common"
---
> More information: <https://forge.rust-lang.org/infra/other-installation-methods.html#rustup>.

- Download and run `rustup-init` to install `rustup` and the default Rust toolchain:

```bash
curl https://sh.rustup.rs -sSf | sh -s
```

- Download and run `rustup-init` and pass arguments to it:

```bash
curl https://sh.rustup.rs -sSf | sh -s -- arguments
```

- Run `rustup-init` and specify additional components or targets to install:

```bash
rustup-init.sh --target target --component component
```

- Run `rustup-init` and specify the default toolchain to install:

```bash
rustup-init.sh --default-toolchain toolchain
```

- Run `rustup-init` and do not install any toolchain:

```bash
rustup-init.sh --default-toolchain none
```

- Run `rustup-init` and specify an installation profile:

```bash
rustup-init.sh --profile minimal|default|complete
```

- Run `rustup-init` without asking for confirmation:

```bash
rustup-init.sh -y
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | rustup-init.sh: add page (#8259) | 2022-07-28T18:34:26 | [367d020a44ff](https://github.com/tldr-pages/tldr/commit/367d020a44ffb4018516ffee116997f6f5439717)

