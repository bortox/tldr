---
author: ['Nicolas Hansse']
date: 1658675593
title: "ansible-doc"
description: "ansible-doc, Affiche les informations des modules installés dans les librairies Ansible."
categories: "common"
---
> Affiche une liste concise des plugins et leurs description courte.

> Plus d'informations : <https://docs.ansible.com/ansible/latest/cli/ansible-doc.html>.

- Liste les plugins action (modules) disponibles :

```bash
ansible-doc --list
```

- Liste les plugins disponible d'un certain type :

```bash
ansible-doc --type type_de_plugin --list
```

- Affiche les informations sur un plugin action (module) spécifique :

```bash
ansible-doc nom_du_plugin
```

- Affiche les informations sur un plugin avec un certain type :

```bash
ansible-doc --type type_de_plugin nom_du_plugin
```

- Affiche le raccourci playbook d'un plugin action (module) :

```bash
ansible-doc --snippet nom_du_plugin
```

- Affiche les informations sur un plugin action (module) en JSON :

```bash
ansible-doc --json nom_du_plugin
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ansible-doc, ansible-galaxy, ansible-inventory: add French translation (#8217) | 2022-07-24T17:13:13 | [611e628e611b](https://github.com/tldr-pages/tldr/commit/611e628e611b0479a6c6c8cd65ce433a1b2b128c)

