---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "choco outdated"
description: "choco outdated, Überprüfe mit Chocolatey, ob Pakete veraltet sind."
categories: "windows"
---
> Weitere Informationen: <https://chocolatey.org/docs/commands-outdated>.

- Zeige eine Liste von veralteten Paketen im Tabellen-Format:

```bash
choco outdated
```

- Ignoriere angeheftete Pakete in der Ausgabe:

```bash
choco outdated --ignore-pinned
```

- Gib eine eigene Quelle an, mit der die Aktualität der Pakete überprüft wird:

```bash
choco outdated --source source_url|alias
```

- Gib einen Benutzernamen und ein Passwort für die Authentifizierung an:

```bash
choco outdated --user benutzername --password passwort
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[LukBukkit](mailto:luk.bukkit@gmail.com) | choco-outdated: add German translation | 2020-10-13T00:10:19 | [88eda2b52cbc](https://github.com/tldr-pages/tldr/commit/88eda2b52cbc70310a480fd63061c7d602e23e35)

