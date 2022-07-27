---
author: ['Nicolas Hansse']
date: 1633627893
title: "alias, TLDR Pages"
description: "alias, Créé des alias -- mots qui sont remplacés par une commande textuelle."
categories: "common"
---
> Les alias expirent avec la session courante shell, sauf s'il a été défini dans le fichier de configuration shell, par exemple `~/.bashrc`.

> Plus d'informations : <https://tldp.org/LDP/abs/html/aliases.html>.

- Liste tous les alias :

```bash
alias
```

- Crée un alias générique :

```bash
alias mot="commande"
```

- Affiche la commande associée à un alias donné :

```bash
alias mot
```

- Enlève un alias :

```bash
unalias mot
```

- Transforme `rm` en une commande intéractive :

```bash
alias rm="rm -i"
```

- Crée `la` comme un raccourci de `ls -a` :

```bash
alias la="ls -a"
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | alias: add French translation (#6681) | 2021-10-07T19:31:33 | [75bb521bee37](https://github.com/tldr-pages/tldr/commit/75bb521bee3720a83bd71236af934c0516a111fa)

