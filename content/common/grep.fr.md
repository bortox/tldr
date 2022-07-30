---
author: ['Nicolas Kosinski', 'Marco Bonelli', 'bl-ue', 'Patrice Denis', 'marchersimon']
date: 1633592259
title: "grep"
description: "grep, Recherche des motifs dans un texte."
categories: "common"
---
> Supporte des motifs simples et des expressions régulières.

> Plus d'informations : <https://www.gnu.org/software/grep/manual/grep.html>.

- Recherche une chaîne de caractères précise :

```bash
grep chaîne_recherchée chemin/vers/fichier
```

- Recherche en ignorant la casse :

```bash
grep -i chaîne_recherchée chemin/vers/fichier
```

- Recherche récursivement (en ignorant les fichiers non-texte) dans le dossier courant une chaîne de caractères précise :

```bash
grep -RI chaîne_recherchée .
```

- Utilise des expressions régulières étendues (supporte `?`, `+`, `{}`, `()` et `|`) :

```bash
grep -E expression_régulière chemin/vers/fichier
```

- Affiche 3 lignes de [C]ontexte, avant ([B]efore), ou [A]près chaque concordance :

```bash
grep -C|B|A 3 chaîne_recherchée chemin/vers/fichier
```

- Affiche le nom du fichier avec la ligne correspondante pour chaque concordance :

```bash
grep -Hn chaîne_recherchée chemin/vers/fichier
```

- Utilise l'entrée standard au lieu d'un fichier :

```bash
cat chemin/vers/fichier | grep chaîne_recherchée
```

- Inverse le résultat pour exclure des chaînes de caractères spécifiques :

```bash
grep -v chaîne_recherchée
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | grep: edit link (#5782) | 2021-04-18T00:08:17 | [d934ae39644f](https://github.com/tldr-pages/tldr/commit/d934ae39644f2ce38f61505d40642a742e9f4c10)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | grep: add French translation (#3759) | 2020-01-15T21:00:43 | [7f5a2b0eb277](https://github.com/tldr-pages/tldr/commit/7f5a2b0eb277f5734f9ad34d497ec4424499a0a6)

