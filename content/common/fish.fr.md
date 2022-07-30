---
author: ['Neluji']
date: 1635361212
title: "fish"
description: "fish, Friendly Interactive SHell, un interpréteur de ligne de commande, conçu pour être facile à utiliser."
categories: "common"
---
> Plus d'informations : <https://fishshell.com>.

- Démarre une session shell interactive :

```bash
fish
```

- Exécute une commande, puis termine la session :

```bash
fish -c "commande"
```

- Exécute un script :

```bash
fish chemin/vers/le/script.fish
```

- Vérifie les erreurs de syntaxe dans un script :

```bash
fish --no-execute chemin/vers/le/script.fish
```

- Démarre une session shell interactive en mode privé, dans laquelle le shell n'a pas accès à l'historique et n'y écrit rien :

```bash
fish --private
```

- Affiche les informations de version :

```bash
fish --version
```

- Ajoute et exporte une variable d'environnement, qui persiste entre les redémarrages du shell (à exécuter depuis le shell uniquement) :

```bash
set -Ux nom_de_la_variable valeur_de_la_variable
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | Change to imperative voice | 2021-10-27T21:00:12 | [bb2a86359e62](https://github.com/tldr-pages/tldr/commit/bb2a86359e620df6c5463078f52eeeee287b4541)
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | shells (bash, dash, fish, ksh, sh, zsh & histexpand): add French translation | 2021-10-27T21:00:12 | [65264bc826a0](https://github.com/tldr-pages/tldr/commit/65264bc826a08f99724adb5892927a865c5960ea)

