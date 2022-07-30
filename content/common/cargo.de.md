---
author: ['Daniel Wolbach', 'Nicolas Kosinski', 'marchersimon']
date: 1631521281
title: "cargo"
description: "cargo, Verwalte Rust-Projekte und deren Abhängigkeiten (crates)."
categories: "common"
---
> Manche Unterbefehle wie `cargo build` sind separat dokumentiert.

> Weitere Informationen: <https://crates.io/>.

- Suche nach Abhängigkeiten (crates):

```bash
cargo search suche
```

- Installiere eine Abhängigkeit (crate):

```bash
cargo install abhängigkeit
```

- Liste alle installierten Abhängigkeiten (crates) auf:

```bash
cargo install --list
```

- Erzeuge ein neues Rust-Projekt als Anwendung oder Bibliothek im aktuellen Verzeichnis:

```bash
cargo init --bin|lib
```

- Erzeuge ein neues Rust-Projekt als Anwendung oder Bibliothek im angegebenen Verzeichnis:

```bash
cargo new pfad/zu/verzeichnis --bin|lib
```

- Erstelle (bzw. kompiliere) ein Rust-Projekt im aktuellen Verzeichnis:

```bash
cargo build
```

- Erstelle (bzw. kompiliere) ein Rust-Projekt mit einer bestimmten Anzahl an Threads (standardmäßig die Anzahl der CPU-Kerne):

```bash
cargo build --jobs thread_anzahl
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Nicolas Kosinski](mailto:nicokosi@users.noreply.github.com) | cargo: use long options everywhere (#6502) | 2021-09-11T09:53:04 | [d3460ef8f103](https://github.com/tldr-pages/tldr/commit/d3460ef8f103a660f6f6765265b838b919342f1a)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Daniel Wolbach](mailto:daniel.wolbach@mailo.com) | cargo: add German translation (#4664) | 2020-10-12T23:07:35 | [978233510e26](https://github.com/tldr-pages/tldr/commit/978233510e26d956e98d979c0b0d90d5c3b51bd0)

