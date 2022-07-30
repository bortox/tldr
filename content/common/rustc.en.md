---
author: ['Axel Navarro', 'pxgamer', 'Daniel Campoverde [alx741]']
date: 1599784268
title: "rustc"
description: "rustc, The Rust compiler."
categories: "common"
---
> Processes, compiles and links Rust language source files.

> More information: <https://doc.rust-lang.org/rustc>.

- Compile a single file:

```bash
rustc file.rs
```

- Compile with high optimization:

```bash
rustc -O file.rs
```

- Compile with debugging information:

```bash
rustc -g file.rs
```

- Compile with architecture-specific optimizations for the current CPU:

```bash
rustc -C target-cpu=native path/to/file.rs
```

- Display architecture-specific optimizations for the current CPU:

```bash
rustc -C target-cpu=native --print cfg
```

- Display target list:

```bash
rustc --print target-list
```

- Compile for a specific target:

```bash
rustc --target target_triple path/to/file.rs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | rustc: add target, target-cpu and print examples (#4320) | 2020-09-11T02:31:08 | [8b4481dc3fa0](https://github.com/tldr-pages/tldr/commit/8b4481dc3fa06e5e4626792190d08c941c7384a1)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | rustc: add link to homepage | 2019-05-29T14:41:10 | [d41239ed3573](https://github.com/tldr-pages/tldr/commit/d41239ed357375af3c6e1c75d87125fc666b02e3)
[Daniel Campoverde [alx741]](mailto:alx741@riseup.net) | rustc: remove test harness option | 2016-05-06T18:59:33 | [b5387ef52761](https://github.com/tldr-pages/tldr/commit/b5387ef5276165e149f12abbba5acc06362b6581)
[Daniel Campoverde [alx741]](mailto:alx741@riseup.net) | rustc: improve description | 2016-05-05T19:01:04 | [a923bc13e19f](https://github.com/tldr-pages/tldr/commit/a923bc13e19f26aef5c42e7e69deca5fedaa2ae3)
[Daniel Campoverde [alx741]](mailto:alx741@riseup.net) | rustc: add page | 2016-05-05T03:51:41 | [de5e24796692](https://github.com/tldr-pages/tldr/commit/de5e247966926bd0deb1ef420c234b8a02d674f4)

