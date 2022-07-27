---
author: ['Krzysztof Bociurko']
date: 1604236574
title: "adb, TLDR Pages"
description: "adb, Android Debug Bridge: komunikuj się z instancją emulatora Androida lub podłączonym urządzeniem z Androidem."
categories: "common"
---
> Więcej informacji: <https://developer.android.com/studio/command-line/adb>.

- Sprawdź czy proces serwera adb działa, jeśli nie, uruchom go:

```bash
adb start-server
```

- Zakończ proces serwera adb:

```bash
adb kill-server
```

- Uruchom powłokę w instancji emulatora lub urządzeniu:

```bash
adb shell
```

- Wypchnij aplikację Androidową do instancji emulatora lub urządzenia:

```bash
adb install -r ścieżka/do/pliku.apk
```

- Skopiuj plik/katalog do urządzenia:

```bash
adb pull ścieżka/do/pliku_lub_katalogu_na_urządzeniu ścieżka/do/lokalnego_katalogu
```

- Skopiuj plik/katalog z urządzenia:

```bash
adb push ścieżka/do/pliku_lub_katalogu_na_urządzeniu ścieżka/do/lokalnego_katalogu
```

- Listuj połączone lub emulowane urządzenia:

```bash
adb devices
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | adb, adb-reverse: add polish translation (#4901) | 2020-11-01T14:16:14 | [396dfa0ce1e0](https://github.com/tldr-pages/tldr/commit/396dfa0ce1e0d965cdf90f7458baaa6b5211f900)

