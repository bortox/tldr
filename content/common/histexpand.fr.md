---
author: ['Neluji']
date: 1635361212
title: "history expansion, TLDR Pages"
description: "history expansion, Réutiliser et développer l'historique des commandes shell dans `sh`, `bash`, `zsh`, `rbash` et `ksh`."
categories: "common"
---
> Plus d'informations : <https://www.gnu.org/software/bash/manual/html_node/History-Interaction>.

- Exécute de nouveau la commande précédente en tant que root (`!!` est remplacé par la commande précédente) :

```bash
sudo !!
```

- Exécute une commande avec le dernier argument de la commande précédente :

```bash
commande !$
```

- Exécute une commande avec le premier argument de la commande précédente :

```bash
command !^
```

- Exécute la `n`-ème commande de l'historique, en partant de la plus ancienne :

```bash
!n
```

- Exécute la `n`-ème commande de l'historique, en partant de la plus récente :

```bash
!-n
```

- Exécute la commande contenant `string` la plus récente :

```bash
!?string?
```

- Exécute la commande précédente, en remplaçant `string1` par `string2` :

```bash
^string1^string2^
```

- Effectue une expansion de l'historique, mais affiche la commande qui aurait du être exécutée au lieu de l'exécuter  :

```bash
!-n:p
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | Change to imperative voice | 2021-10-27T21:00:12 | [bb2a86359e62](https://github.com/tldr-pages/tldr/commit/bb2a86359e620df6c5463078f52eeeee287b4541)
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | shells (bash, dash, fish, ksh, sh, zsh & histexpand): add French translation | 2021-10-27T21:00:12 | [65264bc826a0](https://github.com/tldr-pages/tldr/commit/65264bc826a08f99724adb5892927a865c5960ea)

