---
author: ['marchersimon', 'Mia Combeau', 'bl-ue', 'julien', 'Nicolas Kosinski']
date: 1662261055
title: "ftp"
description: "ftp, Outils permettant d'interagir avec un serveur avec le protocole FTP."
categories: "common"
---
> Plus d'informations : <https://manned.org/ftp>.

- Connexion à un serveur FTP :

```bash
ftp ftp.exemple.com
```

- Connexion à un serveur FTP en spécifiant son adresse IP et son port :

```bash
ftp adresse_IP port
```

- Passe en mode de transfert binaire (médias, fichiers compressés, etc) :

```bash
binary
```

- Transfère plusieurs fichiers sans demander de confirmation pour chaque :

```bash
prompt off
```

- Télécharge plusieurs fichiers :

```bash
mget *.png
```

- Téléverse plusieurs fichiers :

```bash
mput *.zip
```

- Supprime plusieurs fichiers sur le serveur distant :

```bash
mdelete *.txt
```

- Renomme un fichier sur le serveur distant :

```bash
rename ancien_fichier nouveau_fichier
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Mia Combeau](mailto:52008667+mcombeau@users.noreply.github.com) | ftp: update French translation (#8436) | 2022-09-04T05:10:55 | [7ad86a7984c5](https://github.com/tldr-pages/tldr/commit/7ad86a7984c51a984045c7cd2de9580a52d30240)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[julien](mailto:git@julienc.io) | ftp: add French translation | 2019-10-27T17:33:39 | [1a93f9715e95](https://github.com/tldr-pages/tldr/commit/1a93f9715e95583debf1c898e9fb119614b46d91)

