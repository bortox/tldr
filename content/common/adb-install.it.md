---
author: ['Andrea']
date: 1603906972
title: "adb install, TLDR Pages"
description: "adb install, Android Debug Bridge Install: Invia pacchetti ad un emulatore Android od ad un dispositivo Android connesso."
categories: "common"
---
> Maggiori informazioni: <https://developer.android.com/studio/command-line/adb>.

- Invia un'applicazione Android ad un emulatore emulatore/Android:

```bash
adb install percorso/al/file.apk
```

- Reinstalla una applicazione esistente, preservandone i dati:

```bash
adb install -r percorso/al/file.apk
```

- Fornisce tutti i permessi elencati nel manifest dell'applicazione:

```bash
adb install -g percorso/al/file.apk
```

- Aggiorna rapidamente un pacchetto installato aggiornando solamente le parti dell'APK che sono cambiate:

```bash
adb install --fastdeploy percorso/al/file.apk
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Andrea](mailto:agnophi@gmail.com) | adb-shell, adb-install: add italian translation | 2020-10-28T18:42:52 | [805f10a0b54a](https://github.com/tldr-pages/tldr/commit/805f10a0b54a6814ecd1fb5501ed4f971df44e6a)

