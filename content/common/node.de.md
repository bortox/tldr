---
author: ['Joachim Schwarm']
date: 1633119508
title: "node, TLDR Pages"
description: "node, Server-seitige JavaScript Plattform (Node.js)."
categories: "common"
---
> Weitere Informationen: <https://nodejs.org>.

- Führe eine JavaScript Datei aus:

```bash
node pfad/zu/datei
```

- Starte eine REPL (Interaktive Shell):

```bash
node
```

- Evaluiere als Argument übergebenen JavaScript Code:

```bash
node -e "code"
```

- Evaluierung und Ausgabe des Ergebnisses. Nützlich, um die Versionen der Abhängigkeiten von Node zu sehen:

```bash
node -p "process.versions"
```

- Aktiviere Inspector und pausiere die Ausführung bis sich ein Debugger verbindet sobald der Quellcode vollständig geparsed ist:

```bash
node --no-lazy --inspect-brk pfad/zu/datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | node: add German translation (#6637) | 2021-10-01T22:18:28 | [57bc3e171e56](https://github.com/tldr-pages/tldr/commit/57bc3e171e56c1d4225fb4547b5b9658f2c70f6e)

