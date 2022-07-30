---
author: ['Alexandre ZANNI', 'Azrael JD', 'marchersimon']
date: 1643292617
title: "sysctl"
description: "sysctl, Liste et modifie les variables d'exécution du noyau."
categories: "linux"
---
> Plus d'informations : <https://manned.org/sysctl.8>.

- Affiche toutes les variables disponibles et leurs valeurs :

```bash
sysctl -a
```

- Définis une variable d'état modifiable du noyau :

```bash
sysctl -w section.modifiable=valeur
```

- Obtiens les gestionnaires de fichiers (handlers) actuellement ouverts :

```bash
sysctl fs.file-nr
```

- Obtiens la limite de nombre de fichiers ouverts simultanément :

```bash
sysctl fs.file-max
```

- Applique les changements de `/etc/sysctl.conf` :

```bash
sysctl -p
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | sysctl: add more information link (#7718) | 2022-01-27T15:10:17 | [c837506fd7c3](https://github.com/tldr-pages/tldr/commit/c837506fd7c335137e6a42ceebe3a6eb3061caaa)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Alexandre ZANNI](mailto:16578570+noraj@users.noreply.github.com) | sysctl: add French translation (#6678) | 2021-10-05T21:52:09 | [e168a701ecea](https://github.com/tldr-pages/tldr/commit/e168a701ecea9ef3510e5fdf48786d1074cb1569)

