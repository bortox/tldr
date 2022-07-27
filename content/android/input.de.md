---
author: ['marchersimon', 'Daniel']
date: 1634914980
title: "input, TLDR Pages"
description: "input, Sende Eventcodes oder Touchscreengesten an ein Android-Gerät."
categories: "android"
---
> Dieser Befehl kann nur mit `adb shell` verwendet werden.

> Weitere Informationen: <https://developer.android.com/reference/android/view/KeyEvent.html#constants_1>.

- Sende einen Eventcode für die Eingabe eines einzelnen Zeichens an ein Gerät:

```bash
input keyevent eventcode
```

- Sende einen Text an ein Gerät (`%s` wird als Leerzeichen verwendet):

```bash
input text "text"
```

- Sende ein einzelnes Tippen auf den Touchscreen an ein Gerät:

```bash
input tap x_pos y_pos
```

- Sende ein Wischen über den Touchscreen an ein Gerät:

```bash
input swipe x_start y_start x_ende y_ende dauer_in_ms
```

- Sende ein langes Tippen auf den Touchscreen an ein Gerät:

```bash
input swipe x_pos y_pos x_pos y_pos dauer_in_ms
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | android/*: add German translation (#5808) | 2021-04-24T21:56:58 | [906ccc19e4a5](https://github.com/tldr-pages/tldr/commit/906ccc19e4a52da93874a6797b29412359e658b4)

