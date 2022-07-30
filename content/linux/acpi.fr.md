---
author: ['Gatien']
date: 1646735393
title: "acpi"
description: "acpi, Affiche l'état de la batterie ou des renseignements sur la température."
categories: "linux"
---
> Plus d'informations : <https://sourceforge.net/projects/acpiclient/files/acpiclient/>.

- Affiche les informations sur la batterie :

```bash
acpi
```

- Affiche les informations sur la température :

```bash
acpi -t
```

- Afficher les informations sur le dispositif de refroidissement :

```bash
acpi -c
```

- Afficher les informations sur le dispositif de refroidissement en Fahrenheit :

```bash
acpi -tf
```

- Afficher toutes les informations :

```bash
acpi -V
```

- Extraye les informations depuis `/proc` au lieu de `/sys` :

```bash
acpi -p
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Gatien](mailto:Gatien.vilain@outlook.fr) | acpi: add French translation (#7857) | 2022-03-08T11:29:53 | [e950f4a08031](https://github.com/tldr-pages/tldr/commit/e950f4a08031b6fa3888ee4cac16f844645cb1a2)

