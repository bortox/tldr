---
author: ['Patrice Denis', 'bl-ue', 'marchersimon', 'Nicolas Kosinski']
date: 1659075216
title: "at, TLDR Pages"
description: "at, Planifie l'exécution d'une commande une fois à un moment donné."
categories: "common"
---
> Le service atd (ou atrun) doit être actif pour l'exécution des commandes planifiées.

> Plus d'informations : <https://manned.org/at>.

- Planifie l'exécution de la commande donnée dans l'entrée standard dans 5 minutes (Appuyer sur `Ctrl + D` une fois la commande inscrite) :

```bash
at now + 5 minutes
```

- Planifie l'exécution d'une commande depuis l'entrée standard (impression echo redirigée dans un tube) aujourd'hui à 10h00 :

```bash
echo "./ma_commande.sh" | at 1000
```

- Planifie l'exécution des commandes inclues dans un [f]ichier pour mardi prochain 21h30 :

```bash
at -f chemin/vers/fichier 9:30 PM Tue
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Patrice Denis](mailto:patrice.denis@gmail.com) | at, ifdown, ifup, ip-address, ip: add French translation (#5505) | 2021-03-27T12:51:16 | [170f5f9ebcfc](https://github.com/tldr-pages/tldr/commit/170f5f9ebcfca1427d1f70e33387134c09795552)

