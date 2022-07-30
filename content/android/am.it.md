---
author: ['gsobell']
date: 1626955901
title: "am"
description: "am, Gestore delle Attività di Android."
categories: "android"
---
> Maggiori informazioni: <https://developer.android.com/studio/command-line/adb#am>.

- Inizia un'attività:

```bash
am start -n com.android.settings/.Settings
```

- Inizia un'attività e e invia dati:

```bash
am start -a android.intent.action.VIEW -d tel:123
```

- Inizia un'attività corrispondente ad un'azione, e in una categoria delineato:

```bash
am start -a android.intent.action.MAIN -c android.intent.category.HOME
```

- Converti un intent in un URI:

```bash
am to-uri -a android.intent.action.VIEW -d tel:123
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[gsobell](mailto:82414189+gsobell@users.noreply.github.com) | am, alacritty, bastet, colordiff, dash, i3, nmtui, radeontop, ufw, zypper: add Italian translation (#6221) | 2021-07-22T14:11:41 | [2682aa5d8c0d](https://github.com/tldr-pages/tldr/commit/2682aa5d8c0d2eddb520a78e38a57f20a6bc7db9)

