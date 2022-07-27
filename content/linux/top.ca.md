---
author: ['Seifer23']
date: 1644117941
title: "top, TLDR Pages"
description: "top, Mostra informació dinàmica en temps real sobre processos executant-se."
categories: "linux"
---
> Més informació: <https://manned.org/top>.

- Inicia top:

```bash
top
```

- No mostra cap procés inactiu o zombie:

```bash
top -i
```

- Mostra només processos pertanyents a un usari donat:

```bash
top -u usuari
```

- Ordena processos per una columna:

```bash
top -o nom_columna
```

- Mostra els fils individuals d'un procés donat:

```bash
top -Hp id_procés
```

- Mostra només els processos amb un(s) PID(s) donat(s), separats per comes. (Normalment no es coneix el PID amb antelació. Aquest exemple l'obté del nom del procés):

```bash
top -p $(pgrep -d ',' nom_procés)
```

- Obté ajuda sobre els commandaments interactius:

```bash
?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

