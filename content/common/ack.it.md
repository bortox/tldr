---
author: ['Schneider', 'Marco Bonelli', 'Simone Ragusa', 'marchersimon']
date: 1633112881
title: "ack"
description: "ack, Un tool di ricerca simile a `grep`, ottimizzato per programmatori."
categories: "common"
---
> Vedi anche: `rg`, che è molto più veloce.

> Maggiori informazioni: <https://beyondgrep.com/documentation>.

- Cerca ricorsivamente file contenenti una stringa o un'espressione regolare nella cartella corrente:

```bash
ack "pattern_di_ricerca"
```

- Cerca un pattern in modalità case-insensitive:

```bash
ack --ignore-case "pattern_di_ricerca"
```

- Cerca righe di testo contenenti un pattern, mostrando solo il testo corrispondente e non il resto della riga:

```bash
ack -o "pattern_di_ricerca"
```

- Limita la ricerca ai file di un tipo specifico:

```bash
ack --type=ruby "pattern_di_ricerca
```

- Non cercare nei file di un tipo specifico:

```bash
ack --type=noruby "pattern_di_ricerca
```

- Conta il numero totale di corrispondenze trovate:

```bash
ack --count --no-filename "pattern_di_ricerca"
```

- Mostra i nomi dei file e il numero di corrispondenze per ogni singolo file:

```bash
ack --count --files-with-matches "pattern_di_ricerca"
```

- Mostra la lista di tutti i valori che possono essere usati con `--type`:

```bash
ack --help-types
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Simone Ragusa](mailto:simone99.as@gmail.com) | 7z, ab, ack: update Italian translation | 2021-04-21T13:05:18 | [d028ac125e63](https://github.com/tldr-pages/tldr/commit/d028ac125e63ed0021d4633038dfa88b407e9100)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\ack.md: add homepage | 2019-05-14T19:40:23 | [64cc46e55cce](https://github.com/tldr-pages/tldr/commit/64cc46e55cce5a01f0319ec352433fd3b8e8cf38)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: add italian translations (#2692) Translated 13 pages into italian: 7z 7za 7zr ab abduco ack adb ag airpaste alias [...] | 2019-01-11T01:34:17 | [1286509fe557](https://github.com/tldr-pages/tldr/commit/1286509fe557aaa701a1ebe07ce0c5c0b7ef6959)

