---
author: ['iulian']
date: 1629042774
title: "todoist"
description: "todoist, Acest program îți permite să folosești Todoist din linia de comandă."
categories: "common"
---
> Mai multe informații: <https://github.com/sachaos/todoist>.

- Adaugă o sarcină:

```bash
todoist add "o_sarcină"
```

- Adaugă o sarcină cu prioritate ridicată cu o etichetă, proiect și dată scadentă:

```bash
todoist add "o_sarcină" --priority 1 --label-ids "idul_etichetei" --project-name "numele_proiectului" --date "tmr 9am"
```

- Adaugă o sarcină cu prioritate ridicată cu o etichetă, proiect și dată scadentă, folosind modul rapid:

```bash
todoist quick '#numele_proiectului "tmr 9am" p1 o_sarcină @numele_etichetei'
```

- Enumeră toate sarcinile cu cap de tabel și culori:

```bash
todoist --header --color list
```

- Enumeră toate sarcinile cu prioritate ridicată:

```bash
todoist list --filter p1
```

- Enumeră toate sarcinile cu prioritate ridicată de astăzi care au eticheta specificată:

```bash
todoist list --filter '(@numele_etichetei | today) & p1'
```
Lista modificărilor aduse acestei documentații.


Autor | Descriere | Format de dată ISO 8601 | Link către GitHub
------|-----|-----|-----
[iulian](mailto:iulian.dita@gmail.com) | todoist: add page (#6361) | 2021-08-15T17:52:54 | [24ba08b5ed1b](https://github.com/tldr-pages/tldr/commit/24ba08b5ed1b4e56a916319f3e2292c31f569885)

