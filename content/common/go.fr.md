---
author: ['melvinxeu']
date: 1641284043
title: "go"
description: "go, Outil de gestion du code source Go."
categories: "common"
---
> Certaines sous-commandes telles que `go build` ont leur propre documentation d'utilisation.

> Plus d'informations : <https://golang.org>.

- Télécharger et installer un paquet, spécifié par son chemin d'importation :

```bash
go get chemin_du_paquet
```

- Compiler et exécuter un fichier source (il doit contenir un paquet `main`) :

```bash
go run fichier.go
```

- Compiler un fichier source dans un exécutable nommé :

```bash
go build -o executable fichier.go
```

- Compile le paquet présent dans le répertoire courant :

```bash
go build
```

- Exécuter tous les cas de test du paquet courant (les fichiers doivent se terminer par `_test.go`) :

```bash
go test
```

- Compiler et installer le paquet actuel :

```bash
go install
```

- Initialiser un nouveau module dans le répertoire courant :

```bash
go mod init nom_du_module
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[melvinxeu](mailto:63373444+melvinxeu@users.noreply.github.com) | go: add French translation (#7487) | 2022-01-04T09:14:03 | [b8eb880db683](https://github.com/tldr-pages/tldr/commit/b8eb880db6835040a6c10edfc78c711a53067b33)

