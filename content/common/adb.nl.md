---
author: ['Charlie', 'bl-ue']
date: 1612369364
title: "adb, TLDR Pages"
description: "adb, Android Debug-Brug: communiceer met een Android-emulator of een aangesloten Android-apparaat."
categories: "common"
---
> Meer informatie: <https://developer.android.com/studio/command-line/adb>.

- Controleer of het adb serverproces draait en start het:

```bash
adb start-server
```

- Sluit het adb serverproces:

```bash
adb kill-server
```

- Start een afstandshell voor de doelemulator of apparaatinstantie:

```bash
adb shell
```

- Stuur een Android-applicatie naar de emulator/het apparaat:

```bash
adb install -r pad/naar/bestand.apk
```

- Kopiëer een bestand/map van het doelapparaat:

```bash
adb pull pad/naar/extern/bestand_of_map pad/naar/lokaal/bestand_of_map
```

- Kopiëer een bestand/map naar het doelapparaat:

```bash
adb push pad/naar/lokaal/bestand_of_map pad/naar/extern/bestand_of_map
```

- Krijg een lijst met aangesloten apparaten:

```bash
adb devices
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Charlie](mailto:10348289+Cxarli@users.noreply.github.com) | 7z, adb, bash, cargo, cd: add Dutch translation (#4913) | 2020-11-01T15:35:52 | [b854a40530cb](https://github.com/tldr-pages/tldr/commit/b854a40530cbc5895537147ea2fb16d038003e83)

