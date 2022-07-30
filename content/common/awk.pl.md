---
author: ['Michal']
date: 1587299476
title: "awk"
description: "awk, Wszechstronny język programowania do pracy na plikach."
categories: "common"
---
> Więcej informacji: <https://github.com/onetrueawk/awk>.

- Wydrukuj piątą kolumnę (aka. pole) w pliku oddzielonym spacjami:

```bash
awk '{print $5}' nazwapliku
```

- Wydrukuj drugą kolumnę wierszy zawierających "something" w pliku oddzielonym spacjami:

```bash
awk '/coś/ {print $2}' nazwapliku
```

- Wydrukuj ostatnią kolumnę każdego wiersza w pliku, używając przecinka (zamiast spacji) jako separatora pola:

```bash
awk -F ',' '{print $NF}' nazwapliku
```

- Zsumuj wartości w pierwszej kolumnie pliku i wydrukuj sumę:

```bash
awk '{s+=$1} END {print s}' nazwapliku
```

- Zsumuj wartości w pierwszej kolumnie i wydrukuj wartości, a następnie sumę:

```bash
awk '{s+=$1; print $1} END {print "--------"; print s}' nazwapliku
```

- Drukuj co trzeci wiersz, zaczynając od pierwszego wiersza:

```bash
awk 'NR%3==1' nazwapliku
```

- Wydrukuj wszystkie wartości, zaczynając od trzeciej kolumny:

```bash
awk '{for (i=3; i <= NF; i++) printf $i""FS; print""}' nazwapliku
```

- Wydrukuj różne wartości w zależności od warunków:

```bash
awk '{if ($1 == "foo") print "Dokładne dopasowanie foo"; else if ($1 ~ "bar") print "Częściowe dopasowanie bar"; else print "Baz"}' nazwapliku
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Michal](mailto:mich.biesiada@gmail.com) | update awk updated | 2020-04-19T14:31:16 | [1a0ff4ff84bd](https://github.com/tldr-pages/tldr/commit/1a0ff4ff84bd78ea9380a9d8d1c847d5f101aa8c)
[Michal](mailto:mich.biesiada@gmail.com) | update awk updated | 2020-04-19T14:31:16 | [60f01d5f03cc](https://github.com/tldr-pages/tldr/commit/60f01d5f03cc8e06be546847bd290e0a219cb1ee)
[Michal](mailto:mich.biesiada@gmail.com) | create awk.md initial | 2020-04-19T14:31:16 | [128cc7f0eaed](https://github.com/tldr-pages/tldr/commit/128cc7f0eaed1769200d9b76abefe191bc1778c9)

