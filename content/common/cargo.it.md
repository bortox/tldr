---
author: ['Schneider', 'Nicolas Kosinski', 'Franz', 'Marco Bonelli']
date: 1633438869
title: "cargo"
description: "cargo, Gestore di pacchetti di Rust."
categories: "common"
---
> Gestisce progetti Rust ed i moduli dai quali sono dipendenti (detti crate).

> Alcuni comandi aggiuntivi, come `cargo build`, hanno la propria documentazione.

> Maggiori informazioni: <https://crates.io/>.

- Cerca una crate:

```bash
cargo search termine_di_ricerca
```

- Installa una crate:

```bash
cargo install nome_crate
```

- Elenca crate installate:

```bash
cargo install --list
```

- Crea un nuovo progetto Rust binario o di libreria nella directory corrente:

```bash
cargo init --bin|lib
```

- Crea un nuovo progetto Rust binario o di libreria nella directory specificata:

```bash
cargo new path/a/directory --bin|lib
```

- Builda il progetto Rust nella cartella corrente:

```bash
cargo build
```

- Builda utilizzando più job (thread) paralleli:

```bash
cargo build --jobs numero_job
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Franz](mailto:franz.f1032@gmail.com) | *: mention subcommands in Italian translation (#6804) | 2021-10-05T15:01:09 | [e13e67b1711e](https://github.com/tldr-pages/tldr/commit/e13e67b1711e4112cca0cc4d07521c0cf901290c)
[Nicolas Kosinski](mailto:nicokosi@users.noreply.github.com) | cargo: use long options everywhere (#6502) | 2021-09-11T09:53:04 | [d3460ef8f103](https://github.com/tldr-pages/tldr/commit/d3460ef8f103a660f6f6765265b838b919342f1a)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\cargo.md: add homepage | 2019-05-14T19:40:23 | [67a57a9f9ca0](https://github.com/tldr-pages/tldr/commit/67a57a9f9ca0a43edf9d7f31ba90f79bdc15608a)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | cargo: add Italian translation. | 2019-01-28T19:10:19 | [c3ea7d15ab64](https://github.com/tldr-pages/tldr/commit/c3ea7d15ab64e1294ae62b3b9270d579f456ba94)

