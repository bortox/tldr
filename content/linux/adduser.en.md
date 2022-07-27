---
author: ['Waldir Pimenta', 'Patrice Denis', 'Risen-phoenix', 'Andrey Bienkowski', "Marco D'Agostini"]
date: 1644631154
title: "adduser, TLDR Pages"
description: "adduser, User addition utility."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/adduser/adduser.html>.

- Create a new user with a default home directory and prompt the user to set a password:

```bash
adduser username
```

- Create a new user without a home directory:

```bash
adduser --no-create-home username
```

- Create a new user with a home directory at the specified path:

```bash
adduser --home path/to/home username
```

- Create a new user with the specified shell set as the login shell:

```bash
adduser --shell path/to/shell username
```

- Create a new user belonging to the specified group:

```bash
adduser --ingroup group username
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andrey Bienkowski](mailto:hexagonrecursion@gmail.com) | adduser: remove invalid example (#7761) | 2022-02-12T02:59:14 | [78b4e559645c](https://github.com/tldr-pages/tldr/commit/78b4e559645c611a257019d851c164d7e43e6dfa)
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[Marco D'Agostini](mailto:madacol10@gmail.com) | adduser: new example: add user to group (#3044) | 2019-05-21T15:51:06 | [7f317713a730](https://github.com/tldr-pages/tldr/commit/7f317713a7307c440bb6115669e23e5006af54db)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | adduser: change token from "name" to "username" | 2017-04-19T11:46:08 | [7329c7275fe0](https://github.com/tldr-pages/tldr/commit/7329c7275fe032a3f0214432a0c1992c90b5e746)
[Risen-phoenix](mailto:Risen-phoenix@users.noreply.github.com) | adduser: add page (#1276) | 2017-02-24T08:19:51 | [87340067fecf](https://github.com/tldr-pages/tldr/commit/87340067fecfce467247b45ab3df6238f5bdc480)

