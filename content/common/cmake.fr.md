---
author: ['Neluji']
date: 1636017116
title: "cmake"
description: "cmake, Système de construction logicielle multiplateforme, qui permet de générer des recettes de construction pour les systèmes de construction natifs."
categories: "common"
---
> Plus d'informations : <https://cmake.org/cmake/help/latest/manual/cmake.1.html>.

- Génère une recette de construction `CMakeLists.txt` depuis le répertoire d'un projet :

```bash
cmake chemin/vers/le/répertoire_du_projet
```

- Génère une recette de construction, en définissant le type de construction à `Release` à l'aide d'une variable CMake :

```bash
cmake chemin/vers/le/répertoire_du_projet -D CMAKE_BUILD_TYPE=Release
```

- Utilise une recette déjà générée dans un répertoire donné pour construire les artefacts :

```bash
cmake --build chemin/vers/le/répertoire_de_construction
```

- Installe les artefacts de construction dans `/usr/local/` et retirer les symboles de débogage :

```bash
cmake --install chemin/vers/le/répertoire_de_construction --strip
```

- Installe les artefacts de construction en utilisant un préfixe personnalisé pour les chemins :

```bash
cmake --install chemin/vers/le/répertoire_de_construction --strip --prefix chemin/vers/le/répertoire
```

- Lance une cible de construction personnalisée :

```bash
cmake --build chemin/vers/le/répertoire_de_construction --target nom_de_la_cible
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Neluji](mailto:38362829+Neluji@users.noreply.github.com) | cmake: add French translation (#7286) | 2021-11-04T10:11:56 | [7c4f886e144c](https://github.com/tldr-pages/tldr/commit/7c4f886e144c5c1ebaa9b938dbfff80d851e444d)

