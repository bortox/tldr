---
author: ['Nicolas Hansse']
date: 1642517209
title: "adb shell"
description: "adb shell, Android Debug Bridge Shell: Exécute une commande shell sur une instance d'émulateur Android ou un appareil Android."
categories: "common"
---
> Plus d'informations : <https://developer.android.com/studio/command-line/adb>.

- Démarre une session shell interactive sur l'émulateur/l'appareil :

```bash
adb shell
```

- Récupère toutes les propriétés depuis un émulateur ou un appareil :

```bash
adb shell getprop
```

- Remet toutes les permissions courante à leurs valeurs par défaut :

```bash
adb shell pm reset-permissions
```

- Révoque une permission dangereuse pour une application :

```bash
adb shell pm revoke paquet permission
```

- Déclenche un événement clé :

```bash
adb shell input keyevent code
```

- Nettoie les données d'une application sur un émulateur ou un appareil :

```bash
adb shell pm clear paquet
```

- Démarre une activité sur un émulateur ou un appareil :

```bash
adb shell am start -n paquet/activité
```

- Démarre une activité maison depuis un émulateur ou un appareil :

```bash
adb shell am start -W -c android.intent.category.HOME -a android.intent.action.MAIN
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | adb-install, adb-reverse, adb-shell: add French translation (#7667) | 2022-01-18T15:46:49 | [cf250037d7ba](https://github.com/tldr-pages/tldr/commit/cf250037d7babaca84dfa993414eb9b722be28f2)

