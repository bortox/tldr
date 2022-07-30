---
author: ['Neluji']
date: 1635361212
title: "bash"
description: "bash, Bourne-Again SHell, un interpréteur de ligne de commande compatible avec `sh`."
categories: "common"
---
> Voir aussi `histexpand` pour l'expansion de l'historique.

> Plus d'informations : <https://gnu.org/software/bash/>.

- Démarre une session shell interactive :

```bash
bash
```

- Exécute une commande, puis termine la session :

```bash
bash -c "commande"
```

- Exécute un script :

```bash
bash chemin/vers/le/script.sh
```

- Exécute un script en affichant chaque commande avant de l'exécuter :

```bash
bash -x chemin/vers/le/script.sh
```

- Exécute un script en s'arrêtant à la première erreur :

```bash
bash -e chemin/vers/le/script.sh
```

- Lit et exécute des commandes depuis l'entrée standard `stdin` :

```bash
bash -s
```

- Affiche la version de Bash (`$BASH_VERSION` ne contenant que la version, sans les informations de license):

```bash
bash --version
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | Change to imperative voice | 2021-10-27T21:00:12 | [bb2a86359e62](https://github.com/tldr-pages/tldr/commit/bb2a86359e620df6c5463078f52eeeee287b4541)
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | shells (bash, dash, fish, ksh, sh, zsh & histexpand): add French translation | 2021-10-27T21:00:12 | [65264bc826a0](https://github.com/tldr-pages/tldr/commit/65264bc826a08f99724adb5892927a865c5960ea)

