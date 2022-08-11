---
author: ['Nicolas Hansse']
date: 1660133234
title: "autossh"
description: "autossh, Lance, surveille et redémarre les connections SSH."
categories: "common"
---
> Reconnecte automatiquement pour garder le tunnel de transfert de port ouvert. Accepte toutes les options de `ssh`.

> Plus d'informations : <https://www.harding.motd.ca/autossh>.

- Démarre une session SSH, redémarre quand le port échoue à renvoyer de la data :

```bash
autossh -M port_surveillé "commande_ssh"
```

- Fait suivre un port local vers un port distant, redémarre si nécessaire :

```bash
autossh -M port_surveillé -L port_local:localhost:port_distant utilisateur@hôte
```

- Diverge `autossh` en arrière plan avant de lancer `ssh` et n'ouvre pas de shell distant :

```bash
autossh -f -M port_surveillé -N "commande_ssh"
```

- Démarre en arrière plan, sans surveillance de port et à la place envoie des paquets SSH "keep-alive" toutes les 10 secondes pour détecter les échecs :

```bash
autossh -f -M 0 -N -o "ServerAliveInterval 10" -o "ServerAliveCountMax 3" "commande_ssh"
```

- Démarre en arrière plan, sans surveillance de port ni shell distant et s’arrête si le partage de port échoue :

```bash
autossh -f -M 0 -N -o "ServerAliveInterval 10" -o "ServerAliveCountMax 3" -o ExitOnForwardFailure=yes -L port_local:localhost:port_distant utilisateur@hôte
```

- Démarre en arrière plan, logue la sortie de déboggage d'`autossh` et la sortie verbeuse de `ssh` dans des fichiers :

```bash
AUTOSSH_DEBUG=1 AUTOSSH_LOGFILE=chemin/vers/fichier_logs_autossh.log autossh -f -M port_surveillé -v -E chemin/vers/fichier_logs_ssh.log commande_ssh
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | autossh, avo: add French translation (#8335) | 2022-08-10T14:07:14 | [dfc53520da6e](https://github.com/tldr-pages/tldr/commit/dfc53520da6ef0e8418da10f1a5db4b8cd3e58c1)

