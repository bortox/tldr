---
author: ['Nicolas Hansse']
date: 1658419740
title: "ansible-pull, TLDR Pages"
description: "ansible-pull, Récupère les playbook ansible depuis un dépôt VCS et exécute les en local."
categories: "common"
---
> Plus d'informations : <https://docs.ansible.com/ansible/latest/cli/ansible-pull.html>.

- Récupère le playbook depuis un VCS et exécute le fichier par défaut local.yaml du playbook :

```bash
ansible-pull -U url_du_dépôt
```

- Récupère le playbook depuis un VCS et exécute un playbook spécifique :

```bash
ansible-pull -U url_du_dépôt playbook
```

- Récupère un playbook depuis un VCS sur une branche spécifique et exécute ce dernier :

```bash
ansible-pull -U url_du_dépôt -C branche playbook
```

- Récupère un playbook depuis un VCS, spécifie les fichiers hôtes et exécute un playbook spécifique :

```bash
ansible-pull -U url_du_dépôt -i fichier_hôtes playbook
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ansible-playbook, ansible-pull, ansible-vault: add French translation (#8222) * ansible-playbook, ansible-pull, ansible-vault: add [...] | 2022-07-21T18:09:00 | [11e8cacea6a8](https://github.com/tldr-pages/tldr/commit/11e8cacea6a805ef69491a885b116f5f5e4b287f)

