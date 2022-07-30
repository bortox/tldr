---
author: ['tof4']
date: 1635360832
title: "dotnet restore"
description: "dotnet restore, Przywracanie zależności i narzędzi dla projektu .NET."
categories: "common"
---
> Więcej informacji: <https://docs.microsoft.com/dotnet/core/tools/dotnet-restore>.

- Przywróć zależności dla projektu lub solucji w bieżącym katalogu:

```bash
dotnet restore
```

- Przywróć zależności dla projektu lub solucji w wybranym katalogu:

```bash
dotnet restore ścieżka/do/projektu_lub_solucji
```

- Przywróć zależnośći pomijając cache zapytań HTTP:

```bash
dotnet restore --no-cache
```

- Wymuś rozwiązanie wszystkich zależności nawet jeśli poprzednie przywracanie zakończyło się sukcesem:

```bash
dotnet restore --force
```

- Ignoruj błędy w trakcie przywracania zależności ze źródeł:

```bash
dotnet restore --ignore-failed-sources
```

- Przywróć zależności z wybranym poziomem szczegółowości logów:

```bash
dotnet restore --verbosity quiet|minimal|normal|detailed|diagnostic
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[tof4](mailto:bartlomiej.tota@outlook.com) | dotnet-build, dotnet-restore, dotnet-publish, dotnet-ef: fixed commands arguments translation | 2021-10-27T20:53:52 | [59fa8a8228c9](https://github.com/tldr-pages/tldr/commit/59fa8a8228c93e61fd2712f5218cbd5a3897b091)
[tof4](mailto:bartlomiej.tota@outlook.com) | dotnet-restore: polish translation | 2021-10-27T20:53:52 | [b487c3e2174f](https://github.com/tldr-pages/tldr/commit/b487c3e2174fb25bd712d05599a8475b80424106)

