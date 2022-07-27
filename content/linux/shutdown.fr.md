---
author: ['marchersimon', 'Nicolas Hansse', 'lincc']
date: 1636372515
title: "shutdown, TLDR Pages"
description: "shutdown, Éteint et redémarre le système."
categories: "linux"
---
> Plus d'informations : <https://manned.org/shutdown.8>.

- Éteint (arrête) immédiatement :

```bash
shutdown -h now
```

- Redémarre immédiatement :

```bash
shutdown -r now
```

- Redémarre dans 5 minutes :

```bash
shutdown -r +5 &
```

- Éteint à 1:00 pm (Utilise un format 24h) :

```bash
shutdown -h 13:00
```

- Annule une opération d'arrêt ou de redémarrage du système en attente :

```bash
shutdown -c
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | shutdown: add French translation (#6682) | 2021-10-05T21:03:12 | [6bc0820258b5](https://github.com/tldr-pages/tldr/commit/6bc0820258b5f01f502a7f3805cc607886227686)

