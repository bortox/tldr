---
author: ['Andrea']
date: 1603906972
title: "adb shell"
description: "adb shell, Android Debug Bridge Shell: Esegue un commando remoto sull'emulatore o dispositivo Android connesso."
categories: "common"
---
> Maggiori informazioni: <https://developer.android.com/studio/command-line/adb>.

- Avvia un interprete di comandi iterativo remoto sull'emulatore/dispositivo:

```bash
adb shell
```

- Fornisce tutte le proprietà dell'emulatore o dispositivo:

```bash
adb shell getprop
```

- Ripristina tutti i permessi di esecuzione ai loro valori predefiniti:

```bash
adb shell pm reset-permissions
```

- Revoca un permesso pericoloso da un'applicazione:

```bash
adb shell pm revoke pacchetto permesso
```

- Attiva un evento chiave:

```bash
adb shell input keyevent keycode
```

- Pulisce i dati di un'applicazione sull'emulatore o dispositivo:

```bash
adb shell pm clear pacchetto
```

- Avvia un'attività sull'emulatore/dispositivo:

```bash
adb shell am start -n pacchetto/attività
```

- Avvia la schermata iniziale sull'emulatore o dispositivo:

```bash
adb shell am start -W -c android.intent.category.HOME -a android.intent.action.MAIN
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Andrea](mailto:agnophi@gmail.com) | adb-shell: fix translation | 2020-10-28T18:42:52 | [7278deaa3463](https://github.com/tldr-pages/tldr/commit/7278deaa3463b1676a732327f0b90e9034220f01)
[Andrea](mailto:agnophi@gmail.com) | adb-shell, adb-install: add italian translation | 2020-10-28T18:42:52 | [805f10a0b54a](https://github.com/tldr-pages/tldr/commit/805f10a0b54a6814ecd1fb5501ed4f971df44e6a)

