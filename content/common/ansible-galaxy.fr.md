---
author: ['Nicolas Hansse']
date: 1658675593
title: "ansible-galaxy, TLDR Pages"
description: "ansible-galaxy, Crée et gère les rôles Ansible."
categories: "common"
---
> Plus d'informations : <https://docs.ansible.com/ansible/latest/cli/ansible-galaxy.html>.

- Installe un rôle :

```bash
ansible-galaxy install nom_d_utilisateur.nom_du_rôle
```

- Enlève un rôle :

```bash
ansible-galaxy remove nom_d_utilisateur.nom_du_rôle
```

- Liste les rôles installés :

```bash
ansible-galaxy list
```

- Recherche pour un role donné :

```bash
ansible-galaxy search nom_du_rôle
```

- Crée un nouveau rôle :

```bash
ansible-galaxy init nom_du_rôle
```

- Récupère les informations sur le rôle d'un utilisateur :

```bash
ansible-galaxy role info nom_d_utilisateur.nom_du_rôle
```

- Récupère les informations d'une collection :

```bash
ansible-galaxy collection info nom_d_utilisateur.nom_de_la_collection
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ansible-doc, ansible-galaxy, ansible-inventory: add French translation (#8217) | 2022-07-24T17:13:13 | [611e628e611b](https://github.com/tldr-pages/tldr/commit/611e628e611b0479a6c6c8cd65ce433a1b2b128c)

