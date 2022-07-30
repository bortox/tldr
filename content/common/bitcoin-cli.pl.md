---
author: ['mrskizzex']
date: 1603543824
title: "bitcoin-cli"
description: "bitcoin-cli, Klient konsolowy do interakcji z demonem Bitcoina poprzez zapytania RPC."
categories: "common"
---
> Używa konfiguracji zdefiniowanej w `bitcoin.conf`.

> Więcej informacji: <https://en.bitcoin.it/wiki/Running_Bitcoin#Command-line_arguments>.

- Wyślij transakcję na dany adres:

```bash
bitcoin-cli sendtoaddress "adres" ilość
```

- Wygeneruj jeden lub więcej bloków:

```bash
bitcoin-cli generate ilość_bloków
```

- Wyświetl informacje o portfelu:

```bash
bitcoin-cli getwalletinfo
```

- Wyświetl wszystkie poprzednie transakcje dostępne do opłacenia transakcji wychodzących:

```bash
bitcoin-cli listunspent
```

- Wyeksportuj dane portfela do pliku tekstowego:

```bash
bitcoin-cli dumpwallet "ścieżka/do/pliku"
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[mrskizzex](mailto:drizztes@gmail.com) | Create bitcoin-cli.md (#4802) bitcoin-cli: add Polish translation | 2020-10-24T14:50:24 | [db99019935bd](https://github.com/tldr-pages/tldr/commit/db99019935bda2ba7aeecd645b1d27bd1f829118)

