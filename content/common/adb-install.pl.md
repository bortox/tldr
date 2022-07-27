---
author: ['Dawid Lemieszek']
date: 1601906463
title: "adb install, TLDR Pages"
description: "adb install, Android Debug Bridge Install: wysyłaj pakiety do instancji emulatora Androida lub podłączonych urządzeń z systemem Android."
categories: "common"
---
> Więcej informacji: <https://developer.android.com/studio/command-line/adb>.

- Wyślij aplikację na Androida do emulatora / urządzenia:

```bash
adb install scieżka/do/pliku.apk
```

- Zainstaluj ponownie istniejącą aplikację, zachowując jej dane:

```bash
adb install -r scieżka/do/pliku.apk
```

- Przyznaj wszystkie uprawnienia wymienione w pliku manifestu aplikacji:

```bash
adb install -g scieżka/do/pliku.apk
```

- Szybko zaktualizuj zainstalowany pakiet, aktualizując tylko te części APK, które się zmieniły:

```bash
adb install --fastdeploy scieżka/do/pliku.apk
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Dawid Lemieszek](mailto:mrszymeq@gmail.com) | adb install: add Polish translation | 2020-10-05T16:01:03 | [58548777a1d2](https://github.com/tldr-pages/tldr/commit/58548777a1d2cf44d60e18ad5ae18b1f93252d86)

