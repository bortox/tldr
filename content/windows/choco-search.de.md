---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "choco search, TLDR Pages"
description: "choco search, Suche mit Chocolatey nach einem lokal oder im Internet verfügbaren Paket."
categories: "windows"
---
> Weitere Informationen: <https://chocolatey.org/docs/commands-search>.

- Suche nach einem Paket:

```bash
choco search suchabfrage
```

- Suche nur lokal nach einem Paket:

```bash
choco search suchabfrage --local-only
```

- Suche nur nach genauen Übereinstimmungen:

```bash
choco search suchabfrage --exact
```

- Stimme allen Fragen automatisch zu:

```bash
choco search suchabfrage --yes
```

- Gib eine eigene Quelle an, welche nach Paketen durchsucht wird:

```bash
choco search suchabfrage --source quell_url|alias
```

- Gib einen Benutzernamen und ein Passwort für die Authentifizierung an:

```bash
choco search suchabfrage --user benutzername --password passwort
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[LukBukkit](mailto:luk.bukkit@gmail.com) | choco-search: add German translation | 2020-10-13T00:10:19 | [a08dc913b661](https://github.com/tldr-pages/tldr/commit/a08dc913b661b9e54b07c3b15aee90ae91ef9a47)

