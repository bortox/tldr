---
author: ['zethra', 'eignnx', 'pxgamer', 'Johannes Lade']
date: 1627564145
title: "rustup, TLDR Pages"
description: "rustup, Rust toolchain installer."
categories: "common"
---
> Install, manage, and update Rust toolchains.

> More information: <https://github.com/rust-lang/rustup.rs>.

- Install the nightly toolchain for your system:

```bash
rustup install nightly
```

- Switch the default toolchain to nightly so that the `cargo` and `rustc` commands will use it:

```bash
rustup default nightly
```

- Use the nightly toolchain when inside the current project, but leave global settings unchanged:

```bash
rustup override set nightly
```

- Update all toolchains:

```bash
rustup update
```

- List installed toolchains:

```bash
rustup show
```

- Run cargo build with a certain toolchain:

```bash
rustup run toolchain_name cargo build
```

- Open the local rust documentation in the default web browser:

```bash
rustup doc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Johannes Lade](mailto:johannes.lade@yahoo.com) | rustup: add doc example (#6273) | 2021-07-29T15:09:05 | [f6bb40c1123c](https://github.com/tldr-pages/tldr/commit/f6bb40c1123c96cab38c59f6bcf43009482e899f)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | rustup: add link to homepage | 2019-05-29T14:41:10 | [0f118dde9912](https://github.com/tldr-pages/tldr/commit/0f118dde9912ad0eb789e5f0e8882c692ac73fe1)
[eignnx](mailto:34199632+eignnx@users.noreply.github.com) | rustup: add override example (#2001) | 2018-02-18T19:35:09 | [b7e73303adab](https://github.com/tldr-pages/tldr/commit/b7e73303adab0f8bc2b763154ff6762ef820212a)
[zethra](mailto:jediben97@gmail.com) | Made requested formatting changes | 2017-11-30T15:51:01 | [58330c9972fd](https://github.com/tldr-pages/tldr/commit/58330c9972fd8e578c285fe90d8eb275cbc6b748)
[zethra](mailto:jediben97@gmail.com) | Changed 'toolchain name' to 'toolchain_name' | 2017-11-29T00:58:06 | [ad7e9b14e102](https://github.com/tldr-pages/tldr/commit/ad7e9b14e10270cd16e530f2908b517705d52c29)
[zethra](mailto:jediben97@gmail.com) | Fixed formating | 2017-11-28T00:29:43 | [9ba419d4bd11](https://github.com/tldr-pages/tldr/commit/9ba419d4bd11cfc79b5a596e91dcb0ed9f9c2544)
[zethra](mailto:jediben97@gmail.com) | Added page for rustup | 2017-11-27T16:02:29 | [b6bc645d83a2](https://github.com/tldr-pages/tldr/commit/b6bc645d83a2e1e7ab75f89fcc610ec0dbb826a2)

