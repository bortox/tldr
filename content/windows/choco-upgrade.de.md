---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "choco upgrade"
description: "choco upgrade, Aktualisiere mit Chocolatey ein oder mehrere Pakete."
categories: "windows"
---
> Weitere Informationen: <https://chocolatey.org/docs/commands-upgrade>.

- Aktualisiere ein oder mehrere Pakete, deren Namen mit Leerzeichen getrennt sind:

```bash
choco upgrade paket(e)
```

- Aktualisiere auf eine bestimmte Version des Pakets:

```bash
choco upgrade paket --version version
```

- Aktualisiere alle Pakete:

```bash
choco upgrade all
```

- Aktualisiere alle außer den angegebenen, durch Kommas getrennten Paketen:

```bash
choco upgrade all --except "paket(e)"
```

- Stimme allen Fragen automatisch zu:

```bash
choco upgrade paket --yes
```

- Gib eine eigene Quelle an, von der Pakete aktualisiert werden:

```bash
choco upgrade paket --source quell_url|alias
```

- Gib einen Benutzernamen und ein Passwort für die Authentifizierung an:

```bash
choco upgrade paket --user benutzername --password passwort
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[LukBukkit](mailto:luk.bukkit@gmail.com) | choco-upgrade: add German translation | 2020-10-13T00:10:19 | [245b22d5ea47](https://github.com/tldr-pages/tldr/commit/245b22d5ea47c6ca2f9a806870dce996a4ea96dd)

