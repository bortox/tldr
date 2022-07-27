---
author: ['Reinhart Previano Koentjoro', 'Joachim Schwarm', 'Daniel']
date: 1639319694
title: "nvm, TLDR Pages"
description: "nvm, Installiere, deinstalliere oder wechsle zwischen Node.js Versionen."
categories: "common"
---
> Unterstützt Versionsnummern wie "12.8" oder "v16.13.1", und Label wie "stable", "system", etc.

> Weitere Informationen: <https://github.com/creationix/nvm>.

- Installiere eine bestimmte Node.js Version:

```bash
nvm install node_version
```

- Verwende eine bestimmte Node.js Version in der aktuellen Shell:

```bash
nvm use node_version
```

- Setze die Node.js-Standardversion:

```bash
nvm alias default node_version
```

- Zeige alle verfügbaren Node.js Versionen und hebe die Standardversion hervor:

```bash
nvm list
```

- Deinstalliere die angegebene Node.js Version:

```bash
nvm uninstall node_version
```

- Starte eine REPL mit einer bestimmten Node.js Version:

```bash
nvm run node_version --version
```

- Führe ein Skript mit einer bestimmten Node.js Version aus:

```bash
nvm exec node_version node app.js
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | nvm: update versions in command description (#7518) | 2021-12-12T15:34:54 | [a0bb234f064f](https://github.com/tldr-pages/tldr/commit/a0bb234f064feaeb8e225fb28cbb319c481e3dde)
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[Joachim Schwarm](mailto:joachim@schwarm.co) | nvm: add German translation (#6631) | 2021-10-01T22:27:07 | [bfd963353017](https://github.com/tldr-pages/tldr/commit/bfd963353017babcd3749147f0007f8f8f7c1796)

