---
author: ['Nicolas Hansse']
date: 1658419740
title: "ansible-vault"
description: "ansible-vault, Chiffre & déchiffre des valeurs, des structures de données et des fichiers dans un projet Ansible."
categories: "common"
---
> Plus d'informations : <https://docs.ansible.com/ansible/latest/user_guide/vault.html#id17>.

- Crée un nouveau fichier vault chiffré avec une invite à rentrer un mot passe :

```bash
ansible-vault create fichier_vault
```

- Crée un nouveau fichier vault chiffré avec un fichier clé vault pour le chiffrer :

```bash
ansible-vault create --vault-password-file=fichier_de_mot_de_passe fichier_vault
```

- Chiffre un ficher existant avec un fichier de mot de passe optionnel :

```bash
ansible-vault encrypt --vault-password-file=fichier_de_mot_de_passe fichier_vault
```

- Chiffre un texte avec le format de chiffrage pour textes d'Ansible, en affichant une invite interactif :

```bash
ansible-vault encrypt_string
```

- Affiche un fichier chiffré, en utilisant un fichier de mot de passe pour le déchiffrer :

```bash
ansible-vault view --vault-password-file=fichier_de_mot_de_passe fichier_vault
```

- Remplace le fichier de mot de passe d'un fichier vault déjà chiffré par un autre :

```bash
ansible-vault rekey --vault-password-file=ancien_fichier_de_mot_de_passe --new-vault-password-file=nouveau_fichier_de_mot_de_passe fichier_vault
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | ansible-playbook, ansible-pull, ansible-vault: add French translation (#8222) * ansible-playbook, ansible-pull, ansible-vault: add [...] | 2022-07-21T18:09:00 | [11e8cacea6a8](https://github.com/tldr-pages/tldr/commit/11e8cacea6a805ef69491a885b116f5f5e4b287f)

