---
author: ['Wafelack', 'lincc']
date: 1643487459
title: "perl, TLDR Pages"
description: "perl, Interpréteur du langage Perl (version 5)."
categories: "common"
---
> Plus d'informations : <https://www.perl.org>.

- Exécuter le code contenu dans un fichier :

```bash
perl fichier.pl
```

- Vérifier la syntaxe sans exécuter le programme :

```bash
perl -c fichier.pl
```

- Exécuter une expression Perl :

```bash
perl -e expression
```

- Lancer le programme avec le debugger Perl :

```bash
perl -d fichier.pl
```

- Itérer sur toutes les lignes d'un fichier, en les modifiant sur place en utilisant une expression de recherche et de remplacement :

```bash
perl -p -i -e 's/recherche/remplacement' fichier
```

- Lancer une expression de recherche et remplacement sur un fichier, en sauvegardant le fichier original avec une autre extension :

```bash
perl -p -i'.ancien' -e 's/recherche/remplacement/g' fichier
```

- Lancer une expression de recherche et remplacement sur un fichier, en sauvegardant le résultat dans un autre fichier :

```bash
perl -p0e 's/recherche/remplacement/g' fichier_entrée > fichier_sortie
```

- Lancer une expression régulière (RegEx) sur stdin, en affichant le premier groupe capturé pour chaque ligne :

```bash
cat fichier_entrée | perl -nle 'if (/regex/) { print "$1"; last;}'
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Wafelack](mailto:wafelack@riseup.net) | perl: add French translation (#6700) | 2021-10-12T03:53:05 | [90c2c951569b](https://github.com/tldr-pages/tldr/commit/90c2c951569b225fa7d6927c4d18a714708ab068)

