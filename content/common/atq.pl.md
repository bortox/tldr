---
author: ['Krzysztof Bociurko', 'bl-ue', 'marchersimon']
date: 1659075216
title: "atq"
description: "atq, Pokaż oczekujące zadania użytkownika wprowadzone wcześniej przez polecenia `at` lub `batch`."
categories: "common"
---
> Więcej informacji: <https://manned.org/atq>.

- Pokaż zaplanowane zadania:

```bash
atq
```

- Pokaż zadania z kolejki oznaczonej 'a' (kolejki mają jednoznakowe identyfikatory):

```bash
atq -q a
```

- Pokaż zadania wszystkich użytkowników (uruchom jako superużytkownik):

```bash
sudo atq
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | at, atq, atrm, batch: add Polish translation (#4887) | 2020-10-30T11:49:41 | [9a326df50591](https://github.com/tldr-pages/tldr/commit/9a326df50591b12b4be35cf04619cdb492724072)

