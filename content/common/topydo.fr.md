---
author: ['melvinxeu']
date: 1641218826
title: "topydo"
description: "topydo, Une application de liste de choses à faire qui utilise le format todo.txt."
categories: "common"
---
> Plus d'informations : <https://github.com/topydo/topydo>.

- Ajouter une tâche à un projet spécifique avec un contexte donné :

```bash
topydo add "todo_message +projet_nom @context_nom"
```

- Ajouter une tâche à faire avec une date d'échéance de demain et une priorité de `A` :

```bash
topydo add "(A) todo _message due:1d"
```

- Ajouter une tâche à faire dont la date d'échéance est le vendredi :

```bash
topydo add "todo_message due:fri"
```

- Ajouter une tâche répétitive non stricte (jour + récurrence) :

```bash
topydo add "water flowers due:mon rec:1w"
```

- Ajouter une tâche répétitive stricte (prochaine échéance = date + récurrence) :

```bash
topydo add "todo_message due:2020-01-01 rec:+1m"
```

- Revenir sur la dernière commande `topydo` exécutée :

```bash
topydo revert
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[melvinxeu](mailto:63373444+melvinxeu@users.noreply.github.com) | topydo: add French translation (#7490) | 2022-01-03T15:07:06 | [e483985f08cf](https://github.com/tldr-pages/tldr/commit/e483985f08cf1d8292385b08f2c17a29a1ea6cc1)

