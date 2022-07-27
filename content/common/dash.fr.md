---
author: ['Neluji']
date: 1635361212
title: "dash, TLDR Pages"
description: "dash, Debian Almquist SHell, une implémentation de `sh` moderne, conforme à POSIX (non compatible avec Bash)."
categories: "common"
---
> Plus d'informations : <https://manned.org/dash>.

- Démarre une session shell interactive :

```bash
dash
```

- Exécute une commande, puis termine la session :

```bash
dash -c "commande"
```

- Exécute un script :

```bash
dash chemin/vers/le/script.sh
```

- Exécute un script en affichant chaque commande avant de l'exécuter :

```bash
dash -x chemin/vers/le/script.sh
```

- Exécute un script en s'arrêtant à la première erreur :

```bash
dash -e chemin/vers/le/script.sh
```

- Lit et exécute des commandes depuis l'entrée standard `stdin` :

```bash
dash -s
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | Change to imperative voice | 2021-10-27T21:00:12 | [bb2a86359e62](https://github.com/tldr-pages/tldr/commit/bb2a86359e620df6c5463078f52eeeee287b4541)
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | shells (bash, dash, fish, ksh, sh, zsh & histexpand): add French translation | 2021-10-27T21:00:12 | [65264bc826a0](https://github.com/tldr-pages/tldr/commit/65264bc826a08f99724adb5892927a865c5960ea)

