---
author: ['Nicolas Hansse']
date: 1647493224
title: "acme.sh, TLDR Pages"
description: "acme.sh, Script shell implémentant le protocole client ACME, une alternative à certbot."
categories: "common"
---
> Voir aussi `acme.sh dns`.

> Plus d'informations : <https://github.com/acmesh-official/acme.sh>.

- Publie un certificat en utilisant le mode webroot :

```bash
acme.sh --issue --domain exemple.com --webroot /chemin/vers/webroot
```

- Publie un certificat pour plusieurs domaines en utilisant le mode autonome avec le port 80 :

```bash
acme.sh --issue --standalone --domain exemple.com --domain www.exemple.com
```

- Publie un certificat en utilisant le mode autonome TLS avec le port 443 :

```bash
acme.sh --issue --alpn --domain exemple.com
```

- Publie un certificat en utilisant une configuration Nginx :

```bash
acme.sh --issue --nginx --domain exemple.com
```

- Publie un certificat en utilisant une configuration Apache :

```bash
acme.sh --issue --apache --domain exemple.com
```

- Publie un certificat wildcard (\*) en utilisant le mode automatique DNS API :

```bash
acme.sh --issue --dns dns_cf --domain *.exemple.com
```

- Installe les fichiers de certificat dans un dossier spécifique (Utile pour les renouvellements automatiques de certificat) :

```bash
acme.sh --install-cert -d exemple.com --key-file /chemin/vers/exemple.com.key --fullchain-file /chemin/vers/exemple.com.cer --reloadcmd "systemctl force-reload nginx"
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | acme.sh: add French Translation (#7868) | 2022-03-17T06:00:24 | [114f9ec38907](https://github.com/tldr-pages/tldr/commit/114f9ec389077d38c0b8b2215330fd2fe80a36e8)

