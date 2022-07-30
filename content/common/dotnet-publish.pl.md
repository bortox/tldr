---
author: ['tof4']
date: 1635360832
title: "dotnet publish"
description: "dotnet publish, Opublikuj aplikację .NET i jej zależności w celu wdrożenia na docelowym systemie."
categories: "common"
---
> Więcej informacji: <https://docs.microsoft.com/dotnet/core/tools/dotnet-publish>.

- Opublikuj projekt w konfiguracji wydania:

```bash
dotnet publish --configuration Release ścieżka/do/projektu_lub_solucji
```

- Opublikuj projekt z dołączonym wybranym środowiskiem uruchomieniowym:

```bash
dotnet publish --self-contained true --runtime identyfikator_runtime ścieżka/do/projektu_lub_solucji
```

- Zapakuj aplikację do pojedyńczego pliku uruchomieniowego dla konkretnej platformy:

```bash
dotnet publish --runtime identyfikator_runtime -p:PublishSingleFile=true ścieżka/do/projektu_lub_solucji
```

- Pomiń nieużywane biblioteki aby obniżyć rozmiar wdrażanej aplikacji:

```bash
dotnet publish --self-contained true --runtime identyfikator_runtime -p:PublishTrimmed=true ścieżka/do/projektu_lub_solucji
```

- Kompiluj projekt bez przywracania zależności:

```bash
dotnet publish --no-restore ścieżka/do/projektu_lub_solucji
```

- Wybierz katalog docelowy:

```bash
dotnet publish --output ściezka/do/katalogu ścieżka/do/projektu_lub_solucji
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[tof4](mailto:bartlomiej.tota@outlook.com) | dotnet-build, dotnet-restore, dotnet-publish, dotnet-ef: fixed commands arguments translation | 2021-10-27T20:53:52 | [59fa8a8228c9](https://github.com/tldr-pages/tldr/commit/59fa8a8228c93e61fd2712f5218cbd5a3897b091)
[tof4](mailto:bartlomiej.tota@outlook.com) | dotnet-publish: polish translation | 2021-10-27T20:53:52 | [0bd4b57ea339](https://github.com/tldr-pages/tldr/commit/0bd4b57ea3399556f0bf166b087ed212bb6fedef)

