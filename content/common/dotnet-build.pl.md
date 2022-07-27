---
author: ['tof4']
date: 1635360832
title: "dotnet build, TLDR Pages"
description: "dotnet build, Buduj aplikacje .NET i ich zależności."
categories: "common"
---
> Więcej informacji: <https://docs.microsoft.com/dotnet/core/tools/dotnet-build>.

- Kompiluj projekt lub solucje w bieżącym katalogu:

```bash
dotnet build
```

- Kompiluj w konfiguracji debugowania:

```bash
dotnet build ściezka/do/projektu_lub_solucji
```

- Kompiluj w konfiguracji wydania:

```bash
dotnet build --configuration Release
```

- Kompiluj bez przywracania zależności:

```bash
dotnet build --no-restore
```

- Kompiluj z wybranym poziomem szczegółowości logu:

```bash
dotnet build --verbosity quiet|minimal|normal|detailed|diagnostic
```

- Kompiluj dla wybranego środowiska uruchomieniowego:

```bash
dotnet build --runtime identyfikator_runtime
```

- Kompiluj do wybranego katalogu:

```bash
dotnet build --output ścieżka/do/katalogu
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[tof4](mailto:bartlomiej.tota@outlook.com) | dotnet-build, dotnet-restore, dotnet-publish, dotnet-ef: fixed commands arguments translation | 2021-10-27T20:53:52 | [59fa8a8228c9](https://github.com/tldr-pages/tldr/commit/59fa8a8228c93e61fd2712f5218cbd5a3897b091)
[tof4](mailto:bartlomiej.tota@outlook.com) | dotnet-build: polish translation | 2021-10-27T20:53:52 | [60ea275f18a0](https://github.com/tldr-pages/tldr/commit/60ea275f18a057c19fb1b61ea1f44a08bdc0cf8c)

