---
date: 2021-11-17
title: "O TLDR Pages"
description: "Czym jest TLDR Pages? Jak wnieść swój wkład? Co to jest ta strona?"
---

> Ostrzeżenie: ta strona jest automatycznie tłumaczona - w przeciwieństwie do TLDR Pages na tej stronie - więc mogą wystąpić błędy w tłumaczeniu.

![TLDR Pages Logo](/tldr-logo.png)

|Gitter|PRs|Contributors|Build Status|LICENSE|
|---|---|---|---|---|
[![Gitter chat][gitter-image]][gitter-url]|[![Merged PRs][prs-merged-image]][prs-merged-url]|[![GitHub contributors][contributors-image]][contributors-url]|[![Build status][github-actions-image]][github-actions-url]|[![license][license-image]][license-url]

[github-actions-url]: https://github.com/tldr-pages/tldr/actions
[github-actions-image]: https://img.shields.io/github/workflow/status/tldr-pages/tldr/CI.svg
[gitter-url]: https://gitter.im/tldr-pages/tldr
[gitter-image]: https://img.shields.io/badge/chat-on_gitter-deeppink
[prs-merged-url]: https://github.com/tldr-pages/tldr/pulls?q=is:pr+is:merged
[prs-merged-image]: https://img.shields.io/github/issues-pr-closed-raw/tldr-pages/tldr.svg?label=merged+PRs&color=green
[contributors-url]: https://github.com/tldr-pages/tldr/graphs/contributors
[contributors-image]: https://img.shields.io/github/contributors-anon/tldr-pages/tldr.svg
[license-url]: https://github.com/tldr-pages/tldr/blob/main/LICENSE.md
[license-image]: https://img.shields.io/badge/license-CC_BY_4.0-blue.svg
</div>

## Czym jest tldr-pages?

Projekt **tldr-pages** jest zbiorem wspólnie utrzymywanych stron pomocy.
dla narzędzi wiersza poleceń, które stanowią prostsze i bardziej dostępne uzupełnienie tradycyjnych
do tradycyjnych [stron man](https://en.wikipedia.org/wiki/Man_page).

Być może jesteś nowy w świecie linii poleceń? Może jesteś trochę zardzewiały lub nie zawsze pamiętasz argumenty do poleceń takich jak `lsof` czy `tar`?

Na pewno nie pomaga to, że pierwszą opcją wyjaśnioną w `man tar` jest:

```
-b blok
   Określa rozmiar bloku, w rekordach 512-bajtowych, dla operacji we/wy napędu taśmowego.
   Zwykle ten argument jest potrzebny tylko podczas odczytu lub zapisu na napędach taśmowych,
   i zwykle nawet nie wtedy, ponieważ domyślny rozmiar bloku 20 rekordów (10240 bajtów) jest bardzo powszechny.
```

Wydaje się, że jest miejsce na prostsze strony pomocy, które skupiają się na praktycznych przykładach.
Jak o:

![animowany SVG klienta tldr pokazujący polecenie tar](/tldr-tar.svg)

> Stronę TLDR dla polecenia tar można również znaleźć na tej stronie [ten link]("https://tldr.bortox.it/content/common/tar")

To repozytorium jest właśnie tym: stale rosnącą kolekcją przykładów.
dla najczęściej używanych narzędzi wiersza poleceń UNIX, Linux, macOS, SunOS, Android i Windows.

## Co to za strona?

Celem tej strony jest stworzenie TLDR Pages, zbioru zarządzanych przez społeczność stron pomocy
dla narzędzi wiersza poleceń_ dla użytkowników sieci, po prostu wpisując "TLDR pages + command_name" w swoją ulubioną wyszukiwarkę.

Obecnie nie ma możliwości znalezienia strony TLDR polecenia za pomocą prostego wyszukiwania w Google. Sytuacja jest jeszcze gorsza, gdy szukamy polecenia w konkretnym języku innym niż angielski, ponieważ często pojawiają się strony wolne i clickbaitowe.

W rzeczywistości ta strona obsługuje również komentarze i udostępnianie, dzięki czemu strony TLDR są "przyjazne dla sieci". 

### Analiza, monitoring i ogłoszenia

Oczywiście nie ma żadnych **reklam**. 

Śledzenie odbywa się za pomocą Matomo. Matomo jest ustawione tak, aby nie zbierać **danych osobowych**[^1], więc jest zgodne z GDPR i nie wymaga banerowych ciasteczek. Jeśli chcesz zrezygnować, [możesz to zrobić tutaj](https://stats.bortox.it/index.php?module=CoreAdminHome&action=optOut&language=it).

Strona jest **hostowana w Europie**, przez PHP-Friends. Według portalu web-carbon.com, centrum danych wykorzystuje **zrównoważoną energię**!

Jeśli chcesz **wesprzeć** stronę (płacę za serwery), możesz [**dodać coś tutaj**](https://bortox.it/contribuisci-cs-en).

### Dlaczego ta strona?

1. indeksować strony TLDR i uczynić je łatwo wyszukiwalnymi online w wielu językach
2. po prostu napisać coś

### Jak działa ta strona?

* Pliki źródłowe TLDR w Markdown i powiązane z nimi dane Git są odczytywane ze skryptu (30m).
* Strony kompatybilne z Hugo są tworzone przez skrypt
* Hugo tworzy tę stronę (~6500 stron) w zaledwie 10 sekund!

### Możliwe nowe cechy

- [ ] Strony poświęcone konkretnemu zaangażowaniu
- Tłumaczenie automatyczne z DeepL (do 500 000 znaków/miesiąc w wersji darmowej)


## How to use

Popularny i wygodny sposób dostępu do tych stron na własnym komputerze
jest zainstalowanie [klienta Node.js](https://github.com/tldr-pages/tldr-node-client),
który jest wspierany przez opiekunów projektu tldr-pages:

`sh
npm install -g tldr
```

Alternatywnie możesz użyć [klienta Pythona](https://github.com/tldr-pages/tldr-python-client), który może być zainstalowany poprzez `pip3`.

`sh
pip3 install tldr
```

Daje to bezpośredni dostęp do uproszczonego, łatwego do odczytania przewodnika po poleceniach takich jak `tar`,
dostępny przez wpisanie `tldr tar` zamiast normalnego `man tar`.

Jeśli chcesz mieć wersję offline bez instalowania jakiegokolwiek oprogramowania,
patrz [wersja PDF](https://tldr.sh/assets/tldr-book.pdf).

Aby przeglądać strony bez instalowania klienta na komputerze
zobacz klienta sieciowego pod adresem <https://tldr.ostera.io>.

Są też **różni inni klienci**, których zapewnia wspólnota,
zarówno dla linii poleceń, jak i dla innych platform.
Pełna lista klientów znajduje się w naszym [wiki](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients).


## Jak mogę wnieść swój wkład do tldr-pages?

Wszystkie wpłaty są mile widziane!

Niektóre sposoby na wniesienie wkładu to

- Dodanie swojego ulubionego polecenia, które nie zostało uwzględnione.
- Dodanie przykładów lub poprawienie treści istniejącej strony.
- Dodawanie żądanych stron z naszych zagadnień z etykietą [help wanted](https://github.com/tldr-pages/tldr/issues?q=is%3Aopen+jest%3Aissue+label%3A%22help+wanted%22).
- Tłumaczenie stron na różne języki.

Wszystkie strony `tldr` są napisane w Markdown, więc mogą być edytowane dość łatwo, a zmiany mogą być wprowadzane w
z Gitem w linii poleceń lub poprzez
poprzez interfejs internetowy GitHub.

Dążymy do utrzymania [przyjaznej i współpracującej](GOVERNANCE.md) społeczności.
Jeśli jesteś osobą, która po raz pierwszy wnosi swój wkład, zapoznaj się z [Zasadami wnoszenia wkładów](CONTRIBUTING.md) i zacznij działać!

Jeśli chciałbyś przyczynić się do tłumaczenia, możesz <https://lukwebsforge.github.io/tldri18n/>.
aby zobaczyć ogólny postęp wszystkich tłumaczeń i dowiedzieć się, których tłumaczeń brakuje lub są nieaktualne.

## Co oznacza 'tldr'?

TL;DR to skrót od "Za długie; nie czytałem".
Wywodzi się z żargonu internetowego, gdzie jest używany do wskazania, że długi tekst (lub jego części) został
(lub jego części) został pominięty, ponieważ jest zbyt długi.
Więcej informacji w [artykule] autorstwa How-To Geek (https://www.howtogeek.com/435266/what-does-tldr-mean-and-how-do-you-use-it/).

[^1]: Brak logów odwiedzających, śledzenie bez plików cookie, anonimowe adresy IP (2 bajty, jak 192.168.xxx.xxx ) zgodnie z [oficjalnym przewodnikiem matomo](https://matomo.org/faq/new-to-piwik/how-do-i-use-matomo-analytics-without-consent-or-cookie-banner/) ... 