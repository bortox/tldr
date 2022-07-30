---
author: ['Sebastian Göls', 'marchersimon']
date: 1633112881
title: "dotnet"
description: "dotnet, Plattformübergreifende Kommandozeilenandwendungen für .NET Core."
categories: "common"
---
> Manche Unterbefehle wie `dotnet build` sind separat dokumentiert.

> Weitere Informationen: <https://docs.microsoft.com/dotnet/core/tools>.

- Initialisiere ein neues .NET Projekt:

```bash
dotnet new vorlagen_name
```

- Stelle nuget-Pakete wieder her:

```bash
dotnet restore
```

- Baue des .NET Projekt im aktuellen Ordner und führe es aus:

```bash
dotnet run
```

- Führe eine gebaute dotnet-Applikation aus (Benötigt nur die Laufzeitumgebung. Die anderen Befehle benötigen auch den Entwicklungsteil):

```bash
dotnet pfad/zu/anwendung.dll
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Sebastian Göls](mailto:6608231+Abrynos@users.noreply.github.com) | dotnet: add German translation (#4557) | 2020-10-08T13:49:17 | [766026143f60](https://github.com/tldr-pages/tldr/commit/766026143f602bff48d7dad09f94ab6e51e7f465)

