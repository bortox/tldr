---
author: ['Michal', 'lincc']
date: 1629223885
title: "vim, TLDR Pages"
description: "vim, Vim (Vi IMproved), edytor tekstu wiersza polecenia, oferuje kilka trybów dla różnych rodzajów manipulacji tekstem."
categories: "common"
---
> Naciśnięcie przycisku `i` powoduje przejście do trybu edycji. `<Esc>` wraca do normalnego trybu, który nie pozwala na zwykłe wstawianie tekstu.

> Więcej informacji: <https://www.vim.org>.

- Otwórz plik:

```bash
vim sciezka/do/plik
```

- Otwórz plik pod określonym numerem wiersza:

```bash
vim +numer_linii sciezka/do/plik
```

- Zobacz instrukcję pomocy Vim:

```bash
:help<Enter>
```

- Zapisz plik:

```bash
:write<Enter>
```

- Wyjdź bez zapisywania:

```bash
:quit!<Enter>
```

- Cofnij ostatnią operację:

```bash
u
```

- Wyszukaj wzorzec w pliku (naciśnij `n`/`N` przejść do następnego/poprzedniego dopasowania):

```bash
/szukaj_wzorca<Enter>
```

- Wykonaj podstawienie wyrażenia regularnego w całym pliku:

```bash
:%s/wzorzec/zastąpienie/g<Enter>
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | vim: refresh (#6375) | 2021-08-17T20:11:25 | [4ba58f514ad8](https://github.com/tldr-pages/tldr/commit/4ba58f514ad8d22c477708ccc673453bf583a0cb)
[Michal](mailto:mich.biesiada@gmail.com) | update vim updated | 2020-04-19T14:31:16 | [5466591c2107](https://github.com/tldr-pages/tldr/commit/5466591c2107ea36f623487250335144cff2a675)
[Michal](mailto:mich.biesiada@gmail.com) | update vim updated | 2020-04-19T14:31:16 | [1b41e092fb67](https://github.com/tldr-pages/tldr/commit/1b41e092fb679a15fa8ccaa72b956ee2cc585857)
[Michal](mailto:mich.biesiada@gmail.com) | create vim.md initial | 2020-04-19T14:31:16 | [59cd3f3fec64](https://github.com/tldr-pages/tldr/commit/59cd3f3fec64be9d45e005de371e2959804654a2)

