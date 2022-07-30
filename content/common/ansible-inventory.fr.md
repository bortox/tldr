---
author: ['Nicolas Hansse']
date: 1658675593
title: "ansible-inventory"
description: "ansible-inventory, Display or dump an Ansible inventory."
categories: "common"
---
> Voir aussi : `ansible`.

> Plus d'informations : <https://docs.ansible.com/ansible/latest/cli/ansible-inventory.html>.

- Affiche l'inventaire par défaut :

```bash
ansible-inventory --list
```

- Affiche un inventaire spécifique :

```bash
ansbile-inventory --list --inventory chemin/vers/fichier_ou_script_ou_dossier
```

- Affiche l'inventaire par défaut en YAML :

```bash
ansible-inventory --list --yaml
```

- Sauvegarde l'inventaire par défaut dans un fichier :

```bash
ansible-inventory --list --output chemin/vers/fichier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ansible-doc, ansible-galaxy, ansible-inventory: add French translation (#8217) | 2022-07-24T17:13:13 | [611e628e611b](https://github.com/tldr-pages/tldr/commit/611e628e611b0479a6c6c8cd65ce433a1b2b128c)

