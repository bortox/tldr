---
author: ['Stijn-Bch', 'Hugo Dupras', 'CARE-COLIN Thibaut', 'bl-ue', 'marchersimon']
date: 1647264570
title: "git clone"
description: "git clone, Clone un dépôt existant."
categories: "common"
---
> Plus d'informations : <https://git-scm.com/docs/git-clone>.

- Clone un dépôt existant :

```bash
git clone emplacement_du_depot_distant
```

- Clone un dépôt existant dans un répertoire spécifique :

```bash
git clone emplacement_du_depot_distant chemin/vers/repertoire
```

- Clone un dépôt existant et ses sous-modules :

```bash
git clone --recursive emplacement_du_depot_distant
```

- Clone un dépôt local :

```bash
git clone -l chemin/vers/depot/local
```

- Clone silencieusement :

```bash
git clone -q emplacement_du_depot_distant
```

- Clone un dépôt existant en ne récupérant que les 10 commits les plus récents sur la branche par défaut (plus rapide) :

```bash
git clone --depth 10 emplacement_du_depot_distant
```

- Clone un dépôt existant en ne récupérant qu'une branche spécifique :

```bash
git clone --branch nom --single-branch emplacement_du_depot_distant
```

- Clone un dépôt existant en utilisant une commande SSH spécifique :

```bash
git clone --config core.sshCommand="ssh -i chemin/vers/clef_ssh_privee" emplacement_du_depot_distant
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Stijn-Bch](mailto:98285722+Stijn-Bch@users.noreply.github.com) | git-clone, sudo, type: add French translation (#7725) | 2022-03-14T14:29:30 | [5ba1d5e59ca2](https://github.com/tldr-pages/tldr/commit/5ba1d5e59ca238a2428cd1a3bba7a0f568e804f2)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[CARE-COLIN Thibaut](mailto:carecolin@gmail.com) | git*: add French translation (#4619) | 2020-11-10T12:17:06 | [8c8314f72568](https://github.com/tldr-pages/tldr/commit/8c8314f7256871ec042395d6eef6d77827cda04c)
[Hugo Dupras](mailto:jabesq@gmail.com) | Add French translation for git basic commands (#3483) * git-add: Add French translation Signed-off-by: Hugo D. (jabesq) [...] | 2019-12-09T19:14:31 | [8ec0c33e4413](https://github.com/tldr-pages/tldr/commit/8ec0c33e4413536b49901e1f626bd2fec5d73a51)

