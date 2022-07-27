---
author: ['Krzysztof Bociurko']
date: 1635958055
title: "msg, TLDR Pages"
description: "msg, Wyślij wiadomość do wybranego użytnownika lub sesji:"
categories: "windows"
---
> Więcej informacji: <https://docs.microsoft.com/windows-server/administration/windows-commands/msg>.

- Wysyła wiadomość do użytkownika lub sesji:

```bash
msg nazwa_użytkownika|nazwa_sesji|identyfikator_sesji wiadomość
```

- Wyślij wiadomość ze standardowego wejścia

```bash
echo "wiadomość" | msg nazwa_użytkownika|nazwa_sesji|identyfikator_sesji
```

- Wyślij wiadomość to zdalnej maszyny:

```bash
msg /server:nazwa_serwera nazwa_użytkownika|nazwa_sesji|identyfikator_sesji
```

- Wyślij wiadomość do wszystkich użytkowników aktualnej maszyny:

```bash
msg *
```

- Wyślij wiadomość z opóźnieniem:

```bash
msg /time:seconds
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | windows/msg, windows/print, windows/ver: add Polish translation (#7317) | 2021-11-03T17:47:35 | [a9bfab7dc2d3](https://github.com/tldr-pages/tldr/commit/a9bfab7dc2d3d1c1440bbe735b1737bb0b063cc4)

