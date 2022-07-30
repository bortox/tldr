---
author: ['Axel Navarro', 'bl-ue', 'Patrice Denis', 'marchersimon']
date: 1641649180
title: "a2query"
description: "a2query, Retourne la configuration d'exécution d'Apache sur une distribution Debian."
categories: "linux"
---
> Plus d'informations : <https://manpages.debian.org/latest/apache2/a2query.html>.

- Liste les [m]odules Apache actifs :

```bash
sudo a2query -m
```

- Vérifie si un module spécifique est installé :

```bash
sudo a2query -m nom_module
```

- Liste les hôtes virtuels actifs :

```bash
sudo a2query -s
```

- Affiche le [M]odule de traitement multiple actif :

```bash
sudo a2query -M
```

- Affiche la [v]ersion d'Apache :

```bash
sudo a2query -v
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix more information text in French translation (#5773) | 2021-04-25T07:11:35 | [12915f11c283](https://github.com/tldr-pages/tldr/commit/12915f11c2836fedc735ee779e57fd1d8a149cb8)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Patrice Denis](mailto:patrice.denis@gmail.com) | a2query: add French translation | 2021-03-31T18:46:23 | [c53616c0000d](https://github.com/tldr-pages/tldr/commit/c53616c0000d2a71279a04c99630e49e4dc2826e)

