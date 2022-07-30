---
author: ['Charlie', 'Nicolas Kosinski']
date: 1631346784
title: "cargo"
description: "cargo, Rust pakketbeheerder."
categories: "common"
---
> Beheer Rust projecten en hun afhankelijkheden (crates).

> Meer informatie: <https://crates.io/>.

- Zoek naar crates:

```bash
cargo search zoekopdracht
```

- Installeer een crate:

```bash
cargo install crate-naam
```

- Geef een lijst van geïnstalleerde crates:

```bash
cargo install --list
```

- Maak een nieuwe Rust-binary (bin) of -bibliotheek (lib) in de huidige map:

```bash
cargo init --bin|lib
```

- Maak een nieuwe Rust-binary (bin) of -bibliotheek (lib) in de gegeven map:

```bash
cargo new pad/naar/map --bin|lib
```

- Bouw het Rust-project in de huidige map:

```bash
cargo build
```

- Bouw met een gegeven aantal taken. (Standaard is het aantal CPU-kernen):

```bash
cargo build --jobs aantal_taken
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@users.noreply.github.com) | cargo: use long options everywhere (#6502) | 2021-09-11T09:53:04 | [d3460ef8f103](https://github.com/tldr-pages/tldr/commit/d3460ef8f103a660f6f6765265b838b919342f1a)
[Charlie](mailto:10348289+Cxarli@users.noreply.github.com) | 7z, adb, bash, cargo, cd: add Dutch translation (#4913) | 2020-11-01T15:35:52 | [b854a40530cb](https://github.com/tldr-pages/tldr/commit/b854a40530cbc5895537147ea2fb16d038003e83)

