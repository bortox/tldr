---
author: ['Michal', 'marchersimon']
date: 1618756407
title: "arp"
description: "arp, Pokaż i manipuluj pamięcią podręczną ARP systemu."
categories: "common"
---
> Więcej informacji: <https://manned.org/arp>.

- Pokaż bieżącą tabelę arp:

```bash
arp -a
```

- Wyczyść całość cache:

```bash
sudo arp -a -d
```

- Usuń konkretny wpis:

```bash
arp -d adres
```

- Utwórz wpis:

```bash
arp -s adres adres_mac
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | arp: add link | 2021-04-18T16:33:27 | [f06702a5bcc3](https://github.com/tldr-pages/tldr/commit/f06702a5bcc36ee9323d8e467b27e65ed111ef23)
[Michal](mailto:mich.biesiada@gmail.com) | update arp updated | 2020-04-19T14:31:16 | [b956d0d064d0](https://github.com/tldr-pages/tldr/commit/b956d0d064d0eb8a3913dd1c241ab7c0744f4c2b)
[Michal](mailto:mich.biesiada@gmail.com) | update arp updated | 2020-04-19T14:31:16 | [7dcf8772c643](https://github.com/tldr-pages/tldr/commit/7dcf8772c643aaf73ca1594ff1ad2d727c99889c)
[Michal](mailto:mich.biesiada@gmail.com) | create arp.md initial | 2020-04-19T14:31:16 | [9638ee3fa20c](https://github.com/tldr-pages/tldr/commit/9638ee3fa20ca763db695520b94180ad1120fe24)

