---
author: ['Frank Benedikt', 'marchersimon']
date: 1659075216
title: "chromium"
description: "chromium, Open-Source-Webbrowser von Google."
categories: "common"
---
> Weitere Informationen: <https://www.chromium.org/developers/how-tos/run-chromium-with-flags/>.

- Öffne eine html-Datei:

```bash
chromium pfad/zu/datei.html
```

- Öffne eine bestimmte URL:

```bash
chromium beispiel.com
```

- Öffne eine URL im Inkognito-Modus:

```bash
chromium --incognito beispiel.com
```

- Öffne eine URL in einem neuen Fenster:

```bash
chromium --new-window beispiel.com
```

- Öffne eine URL im Anwendungsmodus (ohne Symbolleisten, Suchleiste, Schaltflächen usw.):

```bash
chromium --app='https://beispiel.com'
```

- Öffne eine URL und verwende einen Proxy-Server:

```bash
chromium --proxy-server="socks5://hostname:66" beispiel.com
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Frank Benedikt](mailto:63481435+FrankBG67@users.noreply.github.com) | German translation: alias, bash, borg, cd, chmod, chromium, chsh, convert, exa (#4132) Co-authored-by: Zlatan Vasović [...] | 2020-06-29T23:59:34 | [9aa5907281cb](https://github.com/tldr-pages/tldr/commit/9aa5907281cbaa7a0ee08b5c330c660d779282c7)

