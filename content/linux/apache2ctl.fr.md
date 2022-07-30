---
author: ['Patrice Denis', 'marchersimon']
date: 1633592259
title: "apache2ctl"
description: "apache2ctl, L'outil d'Interface en Lignes de Commandes (ILC) pour administrer le serveur web HTTP Apache."
categories: "linux"
---
> Cette commande est disponible sur une distribution Debian. Pour les distributions basées Red Hat, voir `httpd`.

> Plus d'informations : <https://manpages.debian.org/latest/apache2/apache2ctl.8.en.html>.

- Démarre le démon Apache. Envoie un message s'il est déjà actif :

```bash
sudo apache2ctl start
```

- Arrête le démon Apache :

```bash
sudo apache2ctl stop
```

- Re-démarre le démon Apache :

```bash
sudo apache2ctl restart
```

- Teste la syntaxe du fichier de configuration :

```bash
sudo apache2ctl -t
```

- Liste les modules chargés :

```bash
sudo apache2ctl -M
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix more information text in French translation (#5773) | 2021-04-25T07:11:35 | [12915f11c283](https://github.com/tldr-pages/tldr/commit/12915f11c2836fedc735ee779e57fd1d8a149cb8)
[Patrice Denis](mailto:patrice.denis@gmail.com) | apache2ctl: add French translation | 2021-03-31T18:46:23 | [803a51e783ac](https://github.com/tldr-pages/tldr/commit/803a51e783ac42fdfbeb5d939f51cee83153a929)

