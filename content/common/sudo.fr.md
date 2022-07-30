---
author: ['marchersimon', 'Stijn-Bch']
date: 1659075216
title: "sudo, TLDR Pages"
description: "sudo, Exécute une commande unique en tant que super-utilisateur (super-user) ou un autre utilisateur."
categories: "common"
---
> Plus d'informations : <https://www.sudo.ws/sudo.html>.

- Exécute une commande en tant que super-utilisateur :

```bash
sudo less /var/log/syslog
```

- Édite un fichier en tant que super-utilisateur avec votre éditeur par défaut :

```bash
sudo --edit /etc/fstab
```

- Exécute une commande en tant qu'un autre utilisateur et/ou groupe :

```bash
sudo --user=utilisateur --group=groupe id -a
```

- Répéte la dernière commande préfixée de `sudo` (uniquement dans `bash`, `zsh`, etc.) :

```bash
sudo !!
```

- Lance le terminal par défaut avec des privilèges de super-utilisateur et exécuter des fichiers à profil spécifique (`.profile`, `.bash_profile`, etc.) :

```bash
sudo --login
```

- Lance le terminal par défaut avec des privilèges de super-utilisateur sans modifier l'environnement :

```bash
sudo --shell
```

- Lance le terminal par défaut en tant que l'utilisateur spécifié, en chargeant l'environnement de cet utilisateur et en lisant les fichiers à profil spécifique de cet utilisateur (`.profile`, `.bash_profile`, etc.) :

```bash
sudo --login --user=utilisateur
```

- Liste les commandes autorisées (et interdites) pour l'utilisateur courant :

```bash
sudo --list
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Stijn-Bch](mailto:98285722+Stijn-Bch@users.noreply.github.com) | git-clone, sudo, type: add French translation (#7725) | 2022-03-14T14:29:30 | [5ba1d5e59ca2](https://github.com/tldr-pages/tldr/commit/5ba1d5e59ca238a2428cd1a3bba7a0f568e804f2)

