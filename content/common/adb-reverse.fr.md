---
author: ['Nicolas Hansse']
date: 1642517209
title: "adb reverse, TLDR Pages"
description: "adb reverse, Android Debug Bridge Reverse: Transfère des connections réseaux depuis une instance d'émulateur Android ou un appareil Android."
categories: "common"
---
> Plus d'informations : <https://developer.android.com/studio/command-line/adb>.

- Affiche la liste de toutes les connections réseaux qui sont transféré depuis les émulateurs ou les appareils :

```bash
adb reverse --list
```

- Transfère un port TCP depuis un émulateur ou un appareil vers localhost :

```bash
adb reverse tcp:port_distant tcp:port_local
```

- Supprime une connection socket en cours depuis un émulateur ou un appareil :

```bash
adb reverse --remove tcp:port_distant
```

- Supprime toutes les connections socket depuis tous les émulateurs et appareils :

```bash
adb reverse --remove-all
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | adb-install, adb-reverse, adb-shell: add French translation (#7667) | 2022-01-18T15:46:49 | [cf250037d7ba](https://github.com/tldr-pages/tldr/commit/cf250037d7babaca84dfa993414eb9b722be28f2)

