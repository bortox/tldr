---
author: ['mrskizzex', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "rm, TLDR Pages"
description: "rm, Usuwa pliki lub foldery."
categories: "common"
---
> Więcej informacji: <https://www.gnu.org/software/coreutils/rm>.

- Usuń pliki z dowolnej lokalizacji:

```bash
rm ścieżka/do/pliku ścieżka/do/innego/pliku
```

- Rekursywnie usuń folder oraz wszystkie jego podfoldery:

```bash
rm -r ścieżka/do/folderu
```

- Wymuś usunięcie folderu, bez pytania o potwierdzenie lub pokazywania błędów:

```bash
rm -rf ścieżka/do/folderu
```

- Interaktywnie usuń kilka plików z pytaniem o potwierdzenie przed każdym usunięciem:

```bash
rm -i plik(i)
```

- Usuń pliki w trybie opisowym, pokazując wiadomość o każdym usuniętym pliku:

```bash
rm -v ścieżka/do/folderu/*
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | rm: add link (#5552) | 2021-03-30T09:16:08 | [62668322a827](https://github.com/tldr-pages/tldr/commit/62668322a8278797489c72f005849770fe3f51fb)
[mrskizzex](mailto:drizztes@gmail.com) | rm: add Polish translation (#4810) | 2020-10-24T14:58:02 | [b174740fb4ba](https://github.com/tldr-pages/tldr/commit/b174740fb4bab3cb2f6605c5833e0b3fdaf05203)

