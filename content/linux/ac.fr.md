---
author: ['Gatien']
date: 1646681885
title: "ac"
description: "ac, Affiche les statistiques concernant la durée de connexion des utilisateurs."
categories: "linux"
---
> Plus d'informations : <https://www.gnu.org/software/acct/manual/accounting.html#ac>.

- Affiche pendant combien de temps l'utilisateur actuel a été connecté, en heures :

```bash
ac
```

- Affiche pendant combien de temps les utilisateurs ont été connectés, en heures :

```bash
ac --individual-totals
```

- Affiche pendant combien de temps un utilisateur particulier a été connecté, en heures :

```bash
ac --individual-totals nom_d_utilisateur
```

- Affiche pendant combien de temps un utilisateur particulier a été connecté, en heures par jour (avec le total) :

```bash
ac --daily-totals --individual-totals nom_d_utilisateur
```

- Affiche des détails supplémentaires :

```bash
ac --compatibility
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Gatien](mailto:Gatien.vilain@outlook.fr) | ac: add French translation (#7856) | 2022-03-07T20:38:05 | [b4e8cc64d745](https://github.com/tldr-pages/tldr/commit/b4e8cc64d745b1c341862e4bc0a6994650410ab6)

