---
author: ['Dario Vladović', 'Nicolas Kosinski', 'LomigAndTux', 'bl-ue', 'marchersimon']
date: 1633592259
title: "chown"
description: "chown, Modifie l'utilisateur et le groupe propriétaire des fichiers et dossiers."
categories: "common"
---
> Plus d'informations : <https://www.gnu.org/software/coreutils/chown>.

- Modifie le propriétaire d'un fichier/dossier :

```bash
chown utilisateur chemin/vers/fichier_ou_dossier
```

- Modifie l'utilisateur et le groupe propriétaire d'un fichier/dossier :

```bash
chown utilisateur:groupe chemin/vers/fichier_ou_dossier
```

- Modifie récursivement le propriétaire d'un dossier et de son contenu :

```bash
chown -R utilisateur chemin/vers/dossier
```

- Modifie le propriétaire d'un lien symbolique :

```bash
chown -h utilisateur chemin/vers/lien_symbolique
```

- Modifie le propriétaire d'un fichier / dossier pour correspondre à un fichier de référence :

```bash
chown --reference=chemin/vers/fichier_de_référence chemin/vers/fichier_ou_dossier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chown: add more information link (#5555) | 2021-03-30T15:29:42 | [8d147522d127](https://github.com/tldr-pages/tldr/commit/8d147522d127f65aca087b791bf2deb46a43f59d)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[LomigAndTux](mailto:48161615+LomigAndTux@users.noreply.github.com) | chown: add french translation (#4085) | 2020-06-17T13:14:13 | [4145ed69a901](https://github.com/tldr-pages/tldr/commit/4145ed69a901a3049f85c38d027d43b25f351ef7)

