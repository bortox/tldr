---
author: ['Nicolas Hansse', 'lincc']
date: 1636372515
title: "adb"
description: "adb, Android Debug Bridge: Communiquer avec une instance d'émulateur Android ou un appareil Android."
categories: "common"
---
> Certaines commandes comme `adb shell` ont leur propre documentation.

> Plus d'informations : <https://developer.android.com/studio/command-line/adb>.

- Vérifie si le processus du serveur adb est en fonctionnement et le démarre :

```bash
adb start-server
```

- Arrête le processus du serveur adb :

```bash
adb kill-server
```

- Démarre un shell distant sur l'émulateur/l'appareil ciblé :

```bash
adb shell
```

- Pousse une application Android vers l'émulateur/l'appareil :

```bash
adb install -r chemin/vers/le/fichier.apk
```

- Copie un fichier/dossier depuis l'appareil ciblé :

```bash
adb pull chemin/vers/le/fichier_ou_dossier_de_l'appareil chemin/vers/le/dossier_de_destination_local
```

- Copie un fichier/dossier vers l'appareil ciblé :

```bash
adb push chemin/vers/le/fichier_ou_dossier_local chemin/vers/le/dossier_de_destination_de_l'appareil
```

- Récupère une liste des appareils connectés :

```bash
adb devices
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | subcommand-mention: add French translation (#6820) | 2021-10-07T09:49:53 | [d23184b464a6](https://github.com/tldr-pages/tldr/commit/d23184b464a6de682433dd8125f03fda1e02490f)
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | adb: add French translation (#6680) | 2021-10-05T21:25:31 | [609b1ce28415](https://github.com/tldr-pages/tldr/commit/609b1ce284154151e9daf1e5aa5e74022226b8d1)

