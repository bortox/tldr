---
author: ['Schneider', 'Andrea', 'Franz', 'Marco Bonelli']
date: 1633438869
title: "adb"
description: "adb, Android Debug Bridge: comunica con un'instanza di un emulatore Android o con un dispositivo android connesso."
categories: "common"
---
> Alcuni comandi aggiuntivi, come `adb shell`, hanno la propria documentazione.

> Maggiori informazioni: <https://developer.android.com/studio/command-line/adb>.

- Controlla se il processo server adb è attivo ed avvialo:

```bash
adb start-server
```

- Termina il processo server adb:

```bash
adb kill-server
```

- Avvia una shell remota nell'emulatore o dispositivo target:

```bash
adb shell
```

- Installa un'applicazione Android nell'emulatore o dispositivo target:

```bash
adb install -r percorso/al/file.apk
```

- Copia file o directory dal dispositivo target:

```bash
adb pull percorso/a/file_o_directory_dispositivo percorso/a/file_o_directory_locale
```

- Copia file/directory sul dispositivo target:

```bash
adb push percorso/a/file_o_directory_locale percorso/a/directory_destinazione_dispositivo
```

- Mostra una lista dei dispositivi connessi:

```bash
adb devices
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Franz](mailto:franz.f1032@gmail.com) | *: mention subcommands in Italian translation (#6804) | 2021-10-05T15:01:09 | [e13e67b1711e](https://github.com/tldr-pages/tldr/commit/e13e67b1711e4112cca0cc4d07521c0cf901290c)
[Andrea](mailto:agnophi@gmail.com) | adb: complete italian translation | 2020-10-28T18:42:52 | [c1db578cea6a](https://github.com/tldr-pages/tldr/commit/c1db578cea6a3ef6de4a77f959942e6b382d35db)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\adb.md: add homepage | 2019-05-14T19:40:23 | [28133b45322c](https://github.com/tldr-pages/tldr/commit/28133b45322c32c30f55cff7aef6fde88754b378)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: add italian translations (#2692) Translated 13 pages into italian: 7z 7za 7zr ab abduco ack adb ag airpaste alias [...] | 2019-01-11T01:34:17 | [1286509fe557](https://github.com/tldr-pages/tldr/commit/1286509fe557aaa701a1ebe07ce0c5c0b7ef6959)

