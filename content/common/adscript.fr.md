---
author: ['Nicolas Hansse']
date: 1657896223
title: "adscript"
description: "adscript, Compilateur pour fichiers Adscript."
categories: "common"
---
> Plus d'informations : <https://github.com/Amplus2/Adscript>.

- Compile un fichier vers un fichier objet :

```bash
adscript --output chemin/vers/fichier.o chemin/vers/fichier_source.adscript
```

- Compile et lie un fichier vers un exécutable autonome :

```bash
adscript --executable --output chemin/vers/fichier chemin/vers/fichier_source.adscript
```

- Compile un fichier vers LLVM IR à la place du code machine natif :

```bash
adscript --llvm-ir --output chemin/vers/fichier.ll chemin/vers/fichier_source.adscript
```

- Fait une compilation croisée d'un fichier vers un fichier objet pour une architecture CPU ou un système d'exploitation distant :

```bash
adscript --target-triple i386-linux-elf --output chemin/vers/fichier.o chemin/vers/fichier_source.adscript
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | adguardhome, adscript, ag: add French translation (#8197) | 2022-07-15T16:43:43 | [69d02dd1e288](https://github.com/tldr-pages/tldr/commit/69d02dd1e28808ed632a954eb2d81469518626f2)

