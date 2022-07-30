---
author: ['Neluji']
date: 1634661236
title: "ssh-keygen"
description: "ssh-keygen, Génère des clés SSH. Utilisées entre autres pour l'authentification ou la connexion sans utiliser de mot de passe."
categories: "common"
---
> Plus d'informations : <https://man.openbsd.org/ssh-keygen>.

- Génère une clé de manière interactive :

```bash
ssh-keygen
```

- Génère une clé dans un fichier spécifique :

```bash
ssh-keygen -f ~/.ssh/fichier
```

- Génère une clé ed25519, avec 100 passages de fonction de dérivation de clé:

```bash
ssh-keygen -t ed25519 -a 100
```

- Génère une clé RSA de 4096 bits, avec l'adresse électronique en commentaire:

```bash
ssh-keygen -t dsa|ecdsa|ed25519|rsa -b 4096 -C "commentaire|email"
```

- Retire les clés d'une machine donnée du fichier `known_hosts` des hôtes connus (utile lorsque un hôte déjà enregistré change de clé) :

```bash
ssh-keygen -R hote_distant
```

- Affiche l'empreinte d'une clé sous format d'un hash MD5 :

```bash
ssh-keygen -l -E md5 -f ~/.ssh/fichier
```

- Change le mot de passe d'une clé :

```bash
ssh-keygen -p -f ~/.ssh/fichier
```

- Change le format d'une clé (par exemple du format OPENSSH vers PEM), le fichier étant réécrit :

```bash
ssh-keygen -p -N "" -m PEM -f ~/.ssh/cle_privee_OpenSSH
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | ssh-*: add French translation (#6970) | 2021-10-19T18:33:56 | [7d92295ce701](https://github.com/tldr-pages/tldr/commit/7d92295ce7014b1167a9d6370e83891749412f83)

