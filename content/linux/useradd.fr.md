---
author: ['D34DPlayer', 'bl-ue', 'Patrice Denis', 'marchersimon']
date: 1633592259
title: "useradd"
description: "useradd, Crée un nouvel utilisateur."
categories: "linux"
---
> Plus d'informations : <https://manned.org/useradd>.

- Crée un nouvel utilisateur :

```bash
useradd nom
```

- Crée un nouvel utilisateur avec un dossier home par défaut :

```bash
useradd --create-home nom
```

- Crée un nouvel utilisateur avec le shell spécifié :

```bash
useradd --shell /chemin/vers/shell nom
```

- Crée un nouvel utilisateur qui appartient aux groupes supplémentaires (attention à l'omission des espaces) :

```bash
useradd --groups groupe1,groupe2 nom
```

- Crée un nouvel utilisateur sans un dossier home :

```bash
useradd --no-create-home --system nom
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[D34DPlayer](mailto:d34dplayer@protonmail.com) | useradd: translate arguments and French typo | 2020-10-24T14:27:11 | [5180489bcea2](https://github.com/tldr-pages/tldr/commit/5180489bcea2caf0c37b75c35b5ecbf808ce2ce1)
[D34DPlayer](mailto:d34dplayer@protonmail.com) | useradd: add French translation | 2020-10-24T14:27:11 | [38fc10bf9509](https://github.com/tldr-pages/tldr/commit/38fc10bf9509c8565ced3be604849dbd9d5db292)

