---
author: ['marchersimon', 'bl-ue', 'FloLangenfeld', 'lincc']
date: 1643487459
title: "rsync"
description: "rsync, Transférer des fichiers vers ou depuis un hôte distant (pas entre deux hôtes distants)."
categories: "common"
---
> Peut transférer un ou plusieurs fichiers correspondant à un motif.

> Plus d'informations : <https://manned.org/rsync>.

- Transférer un fichier local vers un serveur distant :

```bash
rsync chemin/vers/fichier_local hote_distant:chemin/vers/dossier_distant
```

- Transférer un fichier d'un serveur distant vers l'hôte local :

```bash
rsync hote_distant:chemin/vers/fichier_distant chemin/vers/dossier_local
```

- Transférer un fichier sous forme d'[a]rchive (pour conserver les attributs) et compressé ([z]ippé), en mode [v]erbeux, lisible par l'[h]umain et afficher la [p]rogression du transfert :

```bash
rsync -azvhP chemin/vers/fichier_local hote_distant:chemin/vers/dossier_distant
```

- Transférer un dossier et tous ses sous-dossiers d'un hôte distant vers l'hôte local :

```bash
rsync -r hote_distant:chemin/vers/dossier_distant chemin/vers/dossier_local
```

- Transférer le contenu d'un dossier (mais pas le dossier lui-même) d'un hôte distant vers un hôte local :

```bash
rsync -r hote_distant:chemin/vers/dossier_distant/ chemin/vers/dossier_local
```

- Transférer un dossier [r]écursivement, dans une [a]rchive pour conserver les attributs, en résolvant les [l]iens symboliques, et ignorant les fichiers déjà transférés sa[u]f si plus récents :

```bash
rsync -rauL hote_distant:chemin/vers/fichier_distant chemin/vers/dossier_local
```

- Transférer un fichier par SSH et effacer les fichiers de l'hôte local qui n'existent pas sur l'hôte distant :

```bash
rsync -e ssh --delete hote_distant:chemin/vers/fichier_distant chemin/vers/fichier_local
```

- Transférer un fichier par SSH et afficher l'avancement global du transfert :

```bash
rsync -e ssh --info=progress2 hote_distant:chemin/vers/fichier_distant chemin/vers/fichier_local
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[FloLangenfeld](mailto:florent.langenfeld@gmail.com) | Bugfix to correct linting error The command "TLDR_LANG=FR tldr rsync " results in the following error: Page common/rsync.md not [...] | 2020-06-07T05:38:58 | [2f7f2d626e49](https://github.com/tldr-pages/tldr/commit/2f7f2d626e496c1df932fc3812c4ec050452c05e)
[FloLangenfeld](mailto:florent.langenfeld@gmail.com) | rsync: add French translation (#4015) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> Co-authored-by: Antoine Amara [...] | 2020-05-10T14:45:44 | [f6bef556a4c4](https://github.com/tldr-pages/tldr/commit/f6bef556a4c4299ac78fd04158849da0048398d7)

