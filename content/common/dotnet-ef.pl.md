---
author: ['tof4']
date: 1635360832
title: "dotnet ef"
description: "dotnet ef, Narzędzia projektowania dla Entity Framework Core."
categories: "common"
---
> Więcej informacji: <https://docs.microsoft.com/ef/core/cli/dotnet>.

- Zaaktualizuj bazę danych do wybranej migracji:

```bash
dotnet ef database update migracja
```

- Wyczyść bazę danych:

```bash
dotnet ef database drop
```

- Wyświetl dostępne `DbContext`:

```bash
dotnet ef dbcontext list
```

- Wygeneruj kod dla `DbContext` oraz typów encji bazy danych:

```bash
dotnet ef dbcontext scaffold connection_string dostawca
```

- Dodaj nową migrację:

```bash
dotnet ef migrations add nazwa
```

- Usuń poprzednią migrację, cofa zmiany w kodzie stworzone dla poprzedniej migracji:

```bash
dotnet ef migrations remove
```

- Wyświetl dostępne migracje:

```bash
dotnet ef migrations list
```

- Wygeneruj skrypt SQL dla zakresu migracji:

```bash
dotnet ef migrations script początkowa_migracja końcowa_migracja
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[tof4](mailto:bartlomiej.tota@outlook.com) | dotnet-build, dotnet-restore, dotnet-publish, dotnet-ef: fixed commands arguments translation | 2021-10-27T20:53:52 | [59fa8a8228c9](https://github.com/tldr-pages/tldr/commit/59fa8a8228c93e61fd2712f5218cbd5a3897b091)
[tof4](mailto:bartlomiej.tota@outlook.com) | dotnet-ef: polish translation | 2021-10-27T20:53:52 | [9203d553015f](https://github.com/tldr-pages/tldr/commit/9203d553015fbd2bd21f06f5cbefb3f6f29055e0)

