---
author: ['Michal', 'Nicolas Kosinski', 'Lucas Gabriel Schneider']
date: 1620113121
title: "http"
description: "http, HTTPie: HTTP client, ma być łatwiejszy w użyciu niż cURL."
categories: "common"
---
> Więcej informacji: <https://httpie.org>.

- Pobierz adres URL do pliku:

```bash
http --download przyklad.org
```

- Wyślij dane zakodowane w formularzu:

```bash
http --form przyklad.org nazwa='bob' zdjecie_profilowe@'bob.png'
```

- Wyślij obiekt JSON:

```bash
http przyklad.org name='bob'
```

- Określ metodę HTTP:

```bash
http HEAD przyklad.org
```

- Dołącz dodatkowy nagłówek:

```bash
http przyklad.org X-MyHeader:123
```

- Podaj nazwę użytkownika i hasło do uwierzytelnienia serwera:

```bash
http --auth nazwauzytkownika:haslo przyklad.org
```

- Określ surowe ciało żądania za pośrednictwem stdin:

```bash
cat dane.txt | http PUT przyklad.org
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | http: use long arguments (#5878) | 2021-05-04T09:25:21 | [a312432c3696](https://github.com/tldr-pages/tldr/commit/a312432c36964fc1d70858b0c8fdec252fe13475)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Michal](mailto:mich.biesiada@gmail.com) | update http updated | 2020-04-19T14:31:16 | [8c6141ea8d82](https://github.com/tldr-pages/tldr/commit/8c6141ea8d82c3824cb2ec02cd6b09f8928f78d0)
[Michal](mailto:mich.biesiada@gmail.com) | update http updated | 2020-04-19T14:31:16 | [ccd20f1f3f40](https://github.com/tldr-pages/tldr/commit/ccd20f1f3f40e557e080ecd5af0f11d4648d45c7)
[Michal](mailto:mich.biesiada@gmail.com) | create http.md initial | 2020-04-19T14:31:16 | [1e23303e5fc5](https://github.com/tldr-pages/tldr/commit/1e23303e5fc5dc9776248cc718573713d4dcb04c)

