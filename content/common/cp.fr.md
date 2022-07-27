---
author: ['Neel Gopaul', 'Dario Vladović', 'Nicolas Kosinski', 'bl-ue', 'marchersimon']
date: 1633592259
title: "cp, TLDR Pages"
description: "cp, Copie des fichiers et des répertoires."
categories: "common"
---
> Plus d'informations : <https://www.gnu.org/software/coreutils/cp>.

- Copier un fichier vers un autre emplacement :

```bash
cp chemin/vers/fichier_source.ext chemin/vers/fichier_cible.ext
```

- Copier un fichier vers un autre répertoire en conservant le nom du fichier :

```bash
cp chemin/vers/fichier_source.ext chemin/vers/répertoire_parent_cible
```

- Copier récursivement le contenu d'un répertoire vers un autre emplacement (si la destination existe, le répertoire est copié à l'intérieur) :

```bash
cp -R chemin/vers/répertoire_source chemin/vers/répertoire_cible
```

- Copier un répertoire récursivement, en mode verbeux (affiche les fichiers au fur et à mesure de leur copie) :

```bash
cp -vR chemin/vers/répertoire_source chemin/vers/répertoire_cible
```

- Copier les fichiers texte vers un autre emplacement, en mode interactif (demande confirmation avant d'écraser) :

```bash
cp -i *.txt chemin/vers/répertoire_cible
```

- Déréférencer les liens symboliques avant de copier :

```bash
cp -L link chemin/vers/répertoire_cible
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | cp: sync French translations with English page (remove "--parents") (#5805) Remove the "--parents" command from the French page since: [...] | 2021-04-22T14:51:51 | [9e4dbe7a9b4c](https://github.com/tldr-pages/tldr/commit/9e4dbe7a9b4ca6127f4532208b6886d7859fb286)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cp: add more information link (#5556) | 2021-03-30T12:30:03 | [ad46ebe87a57](https://github.com/tldr-pages/tldr/commit/ad46ebe87a578bcb5e61d26addcf1bdfe287d75f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Neel Gopaul](mailto:neelmedhanshgopaul@gmail.com) | cp: add French translation (#4684) | 2020-10-15T00:39:07 | [419839411f53](https://github.com/tldr-pages/tldr/commit/419839411f535c10f738109c8c9ba198859072a1)

