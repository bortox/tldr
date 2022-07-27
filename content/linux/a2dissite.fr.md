---
author: ['Patrice Denis', 'marchersimon']
date: 1633592259
title: "a2dissite, TLDR Pages"
description: "a2dissite, Désactive un hôte virtuel Apache sur une distribution Debian."
categories: "linux"
---
> Plus d'informations : <https://manpages.debian.org/latest/apache2/a2dissite.8.en.html>.

- Désactive un hôte virtuel :

```bash
sudo a2dissite virtual_host
```

- N'affiche aucun message (mode silencieux) :

```bash
sudo a2dissite --quiet virtual_host
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: fix more information text in French translation (#5773) | 2021-04-25T07:11:35 | [12915f11c283](https://github.com/tldr-pages/tldr/commit/12915f11c2836fedc735ee779e57fd1d8a149cb8)
[Patrice Denis](mailto:patrice.denis@gmail.com) | a2dissite: add French translation | 2021-03-31T18:46:23 | [fd6b227f4246](https://github.com/tldr-pages/tldr/commit/fd6b227f42469b55296002f1f6b538a2431199dc)

