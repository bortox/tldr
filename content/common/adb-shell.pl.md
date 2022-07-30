---
author: ['Dawid Lemieszek']
date: 1601906463
title: "adb shell"
description: "adb shell, Android Debug Bridge Shell: uruchamiaj zdalne polecenia powłoki na instancji emulatora Androida lub podłączonych urządzeniach z Androidem."
categories: "common"
---
> Więcej informacji: <https://developer.android.com/studio/command-line/adb>.

- Uruchom interaktywną zdalną powłokę na emulatorze / urządzeniu:

```bash
adb shell
```

- Pobierz wszystkie właściwości z emulatora lub urządzenia:

```bash
adb shell getprop
```

- Przywróć wszystkie uprawnienia wykonawcze do ich wartości domyślnych:

```bash
adb shell pm reset-permissions
```

- Odwołaj niebezpieczne pozwolenie dla aplikacji:

```bash
adb shell pm revoke paczka pozwolenie
```

- Wywołaj zdarzenie klawisza:

```bash
adb shell input keyevent kod_klucza
```

- Wyczyść dane aplikacji na emulatorze lub urządzeniu:

```bash
adb shell pm clear paczka
```

- Rozpocznij aktywność na emulatorze / urządzeniu:

```bash
adb shell am start -n paczka/aktywność
```

- Rozpocznij aktywność domową na emulatorze lub urządzeniu:

```bash
adb shell am start -W -c android.intent.category.HOME -a android.intent.action.MAIN
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Dawid Lemieszek](mailto:mrszymeq@gmail.com) | adb shell: add Polish translation | 2020-10-05T16:01:03 | [3d7c8ad744e8](https://github.com/tldr-pages/tldr/commit/3d7c8ad744e81f6abe053b13872e32d03f2f71cf)

