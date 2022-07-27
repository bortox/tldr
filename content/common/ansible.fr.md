---
author: ['Nicolas Kosinski', 'Nicolas Hansse', 'marchersimon', 'Patrice Denis']
date: 1633592259
title: "ansible, TLDR Pages"
description: "ansible, Gestionnaire de groupes d'ordinateurs à distance depuis SSH. (Utiliser le fichier `/etc/ansible/hosts` pour ajouter de nouveaux groupes/hôtes)."
categories: "common"
---
> Certaines commandes comme `ansible galaxy` ont leur propre documentation.

> Plus d'informations : <https://www.ansible.com/>.

- Lister les hôtes appartenant à un groupe :

```bash
ansible groupe --list-hosts
```

- Ping d'un groupe d'hôtes en invoquant le [m]odule "ping" :

```bash
ansible groupe -m ping
```

- Afficher des informations sur un groupe d'hôtes en invoquant le [m]odule "setup" :

```bash
ansible groupe -m setup
```

- Exécuter une commande sur un groupe d'hôtes en invoquant le [m]odule "command" avec en paramètre (a) cette commande :

```bash
ansible groupe -m command -a 'ma_commande'
```

- Exécuter une commande avec des droits administrateur :

```bash
ansible groupe --become --ask-become-pass -m command -a 'ma_commande'
```

- Exécuter une commande en utilisant un fichier d'inventaire personnalisé :

```bash
ansible groupe -i fichier_d'inventaire -m command -a 'ma_commande'
```

- Lister les groupes d'un inventaire :

```bash
ansible localhost -m debug -a 'var=groups.keys()'
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | *: mention subcommands in FR translations (#6823) | 2021-10-06T22:45:59 | [b0e0a6e58cfb](https://github.com/tldr-pages/tldr/commit/b0e0a6e58cfbff6cb7041a4d37b1b46ddac79941)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix more information text in French translation (#5773) | 2021-04-25T07:11:35 | [12915f11c283](https://github.com/tldr-pages/tldr/commit/12915f11c2836fedc735ee779e57fd1d8a149cb8)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | ansible: sync French translation with English page (list groups) (#5804) Also use a simple (and correct) word for "administrative". 😇 | 2021-04-21T14:52:05 | [44a899a35472](https://github.com/tldr-pages/tldr/commit/44a899a354720786993da3e6b0daa55fe72d5ace)
[Patrice Denis](mailto:patrice.denis@gmail.com) | ansible: add French translation (#5494) | 2021-03-24T22:52:12 | [b162d78b7f60](https://github.com/tldr-pages/tldr/commit/b162d78b7f6049089b078f7e0c93364fcac4242a)

