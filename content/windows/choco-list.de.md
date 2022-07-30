---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "choco list"
description: "choco list, Zeige mit Chocolatey eine Liste von Paketen an."
categories: "windows"
---
> Weitere Informationen: <https://chocolatey.org/docs/commands-list>.

- Zeige alle verfügbaren Pakete an:

```bash
choco list
```

- Zeige alle lokal installierten Pakete an:

```bash
choco list --local-only
```

- Zeige eine Liste einschließlich der lokalen Windows-Programme an:

```bash
choco list --include-programs
```

- Zeige nur zugelassene Pakete an:

```bash
choco list --approved-only
```

- Gib eine eigene Quelle an, von der Paket-Informationen abgerufen werden:

```bash
choco list --source quell_url|alias
```

- Gib einen Benutzernamen und ein Passwort für die Authentifizierung an:

```bash
choco list --user benutzername --password passwort
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[LukBukkit](mailto:luk.bukkit@gmail.com) | choco-list: add German translation | 2020-10-13T00:10:19 | [8c4d1c7e103d](https://github.com/tldr-pages/tldr/commit/8c4d1c7e103ddc7cae4814429ceba7222eaebec4)

