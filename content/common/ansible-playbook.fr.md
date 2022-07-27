---
author: ['Nicolas Hansse']
date: 1658419740
title: "ansible-playbook, TLDR Pages"
description: "ansible-playbook, Exécute les tâches définies dans le playbook sur les machines distantes via SSH."
categories: "common"
---
> Plus d'informations : <https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html>.

- Exécute les tâches d'un playbook :

```bash
ansible-playbook playbook
```

- Exécute les tâches d'un playbook avec fichier d'inventaire spécifié :

```bash
ansible-playbook playbook -i fichier_d_inventaire
```

- Exécute les tâches d'un playbook avec des variables supplémentaires définies via la ligne de commande :

```bash
ansible-playbook playbook -e "variable1=valeur1 variable2=valeur2"
```

- Exécute les tâches d'un playbook avec des variables supplémentaires définies dans un fichier JSON :

```bash
ansible-playbook playbook -e "@variables.json"
```

- Exécute les tâches d'un playbook pour certain tags :

```bash
ansible-playbook playbook --tags tag1,tag2
```

- Exécute les tâches d'un playbook en démarrant depuis une certaine tache :

```bash
ansible-playbook playbook --start-at nom_de_la_tache
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ansible-playbook, ansible-pull, ansible-vault: add French translation (#8222) * ansible-playbook, ansible-pull, ansible-vault: add [...] | 2022-07-21T18:09:00 | [11e8cacea6a8](https://github.com/tldr-pages/tldr/commit/11e8cacea6a805ef69491a885b116f5f5e4b287f)

