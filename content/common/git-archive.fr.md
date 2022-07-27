---
author: ['Patrice Denis', 'CARE-COLIN Thibaut', 'Nicolas Kosinski', 'Lucas Gabriel Schneider', 'bl-ue', 'marchersimon']
date: 1633592259
title: "git archive, TLDR Pages"
description: "git archive, Crée une archive de fichiers depuis un branche donnée."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-archive>.

- Crée une archive `.tar` avec le contenu de la HEAD et l'affiche sur la sortie standard :

```bash
git archive --verbose HEAD
```

- Crée une archive `.zip` avec le contenu de la HEAD et l'affiche sur la sortie standard :

```bash
git archive --verbose --format=zip HEAD
```

- Pareil que ci-dessus mais écrit dans l'archive spécifiée :

```bash
git archive --verbose --output=chemin/vers/fichier.zip HEAD
```

- Crée une archive depuis le dernier commit de la branche spécifiée :

```bash
git archive --output=chemin/vers/fichier.tar nom_de_branche
```

- Crée une archive avec le contenu d'un répertoire donné :

```bash
git archive --output=chemin/vers/fichier.tar HEAD:chemin/vers/repertoire
```

- Ajoutez un chemin d'accès à chaque fichier pour l'archiver dans un répertoire spécifique :

```bash
git archive --output=chemin/vers/fichier.tar --prefix=chemin/vers/cible/ HEAD
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)

