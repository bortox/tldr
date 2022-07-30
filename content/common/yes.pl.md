---
author: ['Krzysztof Bociurko']
date: 1635770573
title: "yes"
description: "yes, Wypisuje coś wielokrotnie."
categories: "common"
---
> Komenda używana często aby potwierdzić pytania zadawane przez komendy instalujące takie jak apt-get.

> Więcej informacji: <https://www.gnu.org/software/coreutils/yes>.

- Wypisuje bez końca "wiadomość":

```bash
yes wiadomość
```

- Wypisuje bez końca "y":

```bash
yes
```

- Wysyłaj potwierdzenie dla każdego pytania zadanego przez `apt-get`:

```bash
yes | sudo apt-get install program
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | w, wc, yes: add Polish translation (#7319) | 2021-11-01T13:42:53 | [8bfea7360429](https://github.com/tldr-pages/tldr/commit/8bfea736042993d24ecd736d7e384c3a069732e8)

