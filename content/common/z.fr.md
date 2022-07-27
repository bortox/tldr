---
author: ['Patrice Denis', 'bl-ue', 'marchersimon', 'sebastientinel']
date: 1633592259
title: "z, TLDR Pages"
description: "z, Recherche les répertoires les plus utilisés et permet une navigation rapide à l'aide de chaînes de caractères ou d'expressions régulières."
categories: "common"
---
> Plus d'informations : <https://github.com/rupa/z>.

- Aller dans un répertoire qui contient "foo" dans son nom :

```bash
z foo
```

- Aller dans un répertoire qui contient "foo" et "bar' dans son nom :

```bash
z foo bar
```

- Aller dans le répertoire le mieux classé parmi ceux qui contiennent "foo" dans leurs noms :

```bash
z -r foo
```

- Aller dans le répertoire accédé le plus récemment parmi ceux qui contiennent "foo" dans leurs noms :

```bash
z -t foo
```

- Lis l'ensemble des répertoires dans la base de données `z` qui contiennent "foo" dans leurs noms :

```bash
z -l foo
```

- Supprime le répertoire courant de la base de données de `z` :

```bash
z -x .
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patricedenis@users.noreply.github.com) | multiple pages: fix typos in French translation (#5909) | 2021-06-23T02:34:03 | [a413b9555bc9](https://github.com/tldr-pages/tldr/commit/a413b9555bc9f326904814ecf6dc4f1ba1dc1267)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | z, zip, zless, zola, zopflipng, zoxide: add French translation (#4727) | 2020-10-19T19:04:15 | [ba78b756508c](https://github.com/tldr-pages/tldr/commit/ba78b756508c46ec6a44bd178b7f084fc2e50503)

