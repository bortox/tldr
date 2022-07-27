---
author: ['Michal']
date: 1587299476
title: "autoflake, TLDR Pages"
description: "autoflake, Narzędzie do usuwania nieużywanych importów i zmiennych z kodu Python."
categories: "common"
---
> Więcej informacji: <https://github.com/myint/autoflake>.

- Usuń nieużywane zmienne z jednego pliku i wyświetl różnicę:

```bash
autoflake --remove-unused-variables file.py
```

- Usuń nieużywane importy z wielu plików i wyświetl różnice:

```bash
autoflake --remove-all-unused-imports file1.py file2.py file3.py
```

- Usuń nieużywane zmienne z pliku, zastępując plik:

```bash
autoflake --remove-unused-variables --in-place file.py
```

- Usuń nieużywane zmienne rekurencyjnie ze wszystkich plików w katalogu, nadpisując każdy plik:

```bash
autoflake --remove-unused-variables --in-place --recursive sciezka/do/katalogu
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Michal](mailto:mich.biesiada@gmail.com) | update autoflake updated | 2020-04-19T14:31:16 | [d073844c398c](https://github.com/tldr-pages/tldr/commit/d073844c398cedd94d7dd35936cbdb5ba79ad782)
[Michal](mailto:mich.biesiada@gmail.com) | update autoflake updated | 2020-04-19T14:31:16 | [34966704588a](https://github.com/tldr-pages/tldr/commit/34966704588ae6b6dfeac9f572e21ce5204535ed)
[Michal](mailto:mich.biesiada@gmail.com) | create autoflake.md initial | 2020-04-19T14:31:16 | [a0640f5b3846](https://github.com/tldr-pages/tldr/commit/a0640f5b3846d9c15adf4307b3e6d4cb27427838)

