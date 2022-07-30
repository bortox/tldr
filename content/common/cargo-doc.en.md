---
author: ['Jonathan Dahan']
date: 1577539092
title: "cargo doc"
description: "cargo doc, Build and view Rust package documentation offline."
categories: "common"
---
> More information: <https://doc.rust-lang.org/cargo/commands/cargo-doc.html>.

- Build and view the default package documentation in the browser:

```bash
cargo doc --open
```

- Build documentation without accessing the network:

```bash
cargo doc --offline
```

- View a particular package's documentation:

```bash
cargo doc --open --package package
```

- View a particular package's documentation offline:

```bash
cargo doc --open --offline --package package
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jonathan Dahan](mailto:hi@jonathan.is) | cargo-doc: add page (#3697) Co-authored-by: Agniva De Sarker <agnivade@yahoo.co.in> | 2019-12-28T14:18:12 | [c8931b963edf](https://github.com/tldr-pages/tldr/commit/c8931b963edfeb64bb5bd58182d6e3c3d861aec8)

