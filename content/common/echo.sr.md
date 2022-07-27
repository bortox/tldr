---
author: ['Nemanja']
date: 1633517605
title: "echo, TLDR Pages"
description: "echo, Prikazuje date argumente."
categories: "common"
---
> Više informacija na: <https://www.gnu.org/software/coreutils/echo>.

- Prikazuje tekstualnu poruku. Napomena: navodnici su opcionalni:

```bash
echo "Zdravo Svete"
```

- Prikazuje poruku sa promenljivom:

```bash
echo "Moja lokacija je $PATH"
```

- Prikazuje poruku bez dodatne linije:

```bash
echo -n "Zdravo Svete"
```

- Dodaje poruku u fajl:

```bash
echo "Zdravo Svete" >> fajl.txt
```

- Omogućava interpretaciju posebnih karektera (prethodi im "\\"):

```bash
echo -e "Kolona 1\tKolona 2"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nemanja](mailto:91620216+nebocoder@users.noreply.github.com) | cd, echo, git, link, mkdir: add Serbian translation (#6692) | 2021-10-06T12:53:25 | [68c22b839606](https://github.com/tldr-pages/tldr/commit/68c22b839606a212fd868864a2d3753b34aa35a6)

