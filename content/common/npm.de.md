---
author: ['Nicolas Kosinski', 'Axel Navarro', 'Alessio', 'bl-ue', 'marchersimon']
date: 1643827401
title: "npm"
description: "npm, Ein Kommandozeilenwerkzeug für die Verwaltung von JavaScript und Node.js Paketen (Packages)."
categories: "common"
---
> Weitere Informationen: <https://www.npmjs.com>.

- Erstelle eine `package.json` Datei interaktiv:

```bash
npm init
```

- Installiere alle in der `package.json` Datei gelisteten Abhängigkeiten:

```bash
npm install
```

- Installiere eine spezifische Version eines Packages und füge es automatisch der `package.json` Datei hinzu:

```bash
npm install package_name@version
```

- Installiere ein Package und füge es als Entwicklungs-Abhängigkeit der `package.json` Datei hinzu:

```bash
npm install package_name --save-dev
```

- Installiere ein Package global:

```bash
npm install --global package_name
```

- Deinstalliere ein Package und entferne es automatisch aus der `package.json` Datei:

```bash
npm uninstall package_name
```

- Gib eine Liste aller lokal installierten Packages aus:

```bash
npm list
```

- Gib eine Liste aller global installierten Packages aus:

```bash
npm list --global --depth=0
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | *: use author link instead of npm package (#7730) | 2022-02-02T19:43:21 | [c2c16f61acbd](https://github.com/tldr-pages/tldr/commit/c2c16f61acbdca1933961fbbc20a80bdae76ece5)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | npm: use long argument --global (#5880) | 2021-05-04T09:26:22 | [1fe05c4e59dd](https://github.com/tldr-pages/tldr/commit/1fe05c4e59ddbb8aebbd121f692cd3b743087724)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[Alessio](mailto:25589202+tomadojuice@users.noreply.github.com) | npm: add German translation (#5492) | 2021-03-24T20:35:30 | [f4b334a7c6db](https://github.com/tldr-pages/tldr/commit/f4b334a7c6db04236d1a96beaee5ee9d6be3327b)

