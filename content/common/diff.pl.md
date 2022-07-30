---
author: ['Dawid Lemieszek', 'bl-ue', 'marchersimon']
date: 1633112881
title: "diff"
description: "diff, Porównaj pliki i foldery."
categories: "common"
---
> Więcej informacji: <https://man7.org/linux/man-pages/man1/diff.1.html>.

- Porównaj pliki (lista zmian między `stary_plik` a `nowy_plik`):

```bash
diff stary_plik nowy_plik
```

- Porównaj pliki, ignoruj białe znaki (white spaces):

```bash
diff -w stary_plik nowy_plik
```

- Porównaj pliki, pokaż różnice obok siebie:

```bash
diff -y stary_plik nowy_plik
```

- Porównaj pliki, pokaż różnice w ujednoliconym formacie (tak jak w przypadku `git diff`):

```bash
diff -u stary_plik nowy_plik
```

- Porównaj foldery rekurencyjnie (pokazuje nazwy różniących się plików/folderów a także zmiany w plikach):

```bash
diff -r stary_folder nowy_folder
```

- Porównaj foldery rekurencyjnie, pokaż tylko nazwy plików które się różnią:

```bash
diff -rq stary_folder nowy_folder
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Dawid Lemieszek](mailto:37555757+lemieszek@users.noreply.github.com) | diff: add Polish translation (#4382) | 2020-10-01T20:25:52 | [8e92be9daac6](https://github.com/tldr-pages/tldr/commit/8e92be9daac65c9644f2cb7bec56171229113539)

