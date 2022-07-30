---
author: ['bl-ue', 'Patrice Denis']
date: 1618661981
title: "deluser"
description: "deluser, Rimuovi un account utente o un utente da un gruppo."
categories: "linux"
---
> Maggiori informazioni: <https://manpages.debian.org/latest/adduser/deluser.html>.

- Rimuovi un utente:

```bash
deluser nome
```

- Rimuovi un utente insieme alla sua directory home e raccolta mail:

```bash
deluser -r nome
```

- Rimuovi un utente da un gruppo:

```bash
deluser nome gruppo
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | deluser: sync translations with PR #5245 (#5355) | 2021-03-08T20:49:49 | [c81f9c7b1799](https://github.com/tldr-pages/tldr/commit/c81f9c7b1799a7ff1bc909f372d1f87ec8290365)

