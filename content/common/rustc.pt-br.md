---
author: ['Gabriel Rodrigues']
date: 1634021667
title: "rustc"
description: "rustc, O compilador Rust."
categories: "common"
---
> Processa, compila e vincula arquivos fonte da linguagem Rust.

> Mais informações: <https://doc.rust-lang.org/rustc>.

- Compila um único arquivo:

```bash
rustc arquivo.rs
```

- Compila com alta otimização:

```bash
rustc -O arquivo.rs
```

- Compila com informações de depuração:

```bash
rustc -g arquivo.rs
```

- Compila com otimizações específicas de arquitetura para a CPU atual:

```bash
rustc -C target-cpu=native caminho/para/arquivo.rs
```

- Exibe otimizações específicas de arquitetura para a CPU atual:

```bash
rustc -C target-cpu=native --print cfg
```

- Exibe lista de targets:

```bash
rustc --print target-list
```

- Compila para um target específico:

```bash
rustc --target target_triplo caminho/para/arquivo.rs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gabriel Rodrigues](mailto:78451370+gabxyz@users.noreply.github.com) | dust, rustc: add pt_BR translation (#6848) | 2021-10-12T08:54:27 | [62be7935aa42](https://github.com/tldr-pages/tldr/commit/62be7935aa422a8bde7099fc04b89c0a0788f6c5)

