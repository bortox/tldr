---
author: ['Nicolas Kosinski', 'Patrice Denis', 'marchersimon']
date: 1633592259
title: "whoami"
description: "whoami, Affiche des détails sur l'utilisateur courant."
categories: "windows"
---
> Plus d'informations : <https://docs.microsoft.com/windows-server/administration/windows-commands/whoami>.

- Affiche le nom de l'utilisateur courant :

```bash
whoami
```

- Affiche les groupes pour lesquels l'utilisateur courant est un membre :

```bash
whoami /groups
```

- Affiche les droits de l'utilisateur courant :

```bash
whoami /priv
```

- Affiche le nom principal d'utilisateur (UPN) de l'utilisateur courant :

```bash
whoami /upn
```

- Affiche l'identifiant de connexion de l'utilisateur courant :

```bash
whoami /logonid
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[Patrice Denis](mailto:patrice.denis@gmail.com) | whoami: add French translation (#5495) | 2021-03-24T17:55:41 | [d27e567799b5](https://github.com/tldr-pages/tldr/commit/d27e567799b54653fe30a11f6389d52f356a9fc2)

