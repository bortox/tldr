---
author: ['Michael Schwarz']
date: 1635867633
title: "wsl"
description: "wsl, Verwalte das Windows Subsystem für Linux von der Kommandozeile."
categories: "windows"
---
> Weitere Informationen: <https://docs.microsoft.com/windows/wsl/reference>.

- Starte eine Linux-Shell (in der Standard-Distribution):

```bash
wsl shell_befehl
```

- Führe einen Linux-Befehl aus, ohne eine Shell zu benutzen:

```bash
wsl --exec befehl befehl_argumente
```

- Gib eine bestimmte Distribution an:

```bash
wsl --distribution distribution shell_befehl
```

- Liste verfügbare Distributionen auf:

```bash
wsl --list
```

- Exportiere eine Distribution in eine `.tar` Datei:

```bash
wsl --export distribution pfad/zu/datei.tar
```

- Importiere eine Distribution von einer `.tar` Datei:

```bash
wsl --import distribution pfad/zu/installations_verzeichnis pfad/zu/datei.tar
```

- Ändere die WSL-Version einer bestimmten Distribution:

```bash
wsl --set-version distribution version
```

- Fahre das Windows Subsystem für Linux herunter:

```bash
wsl --shutdown
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Michael Schwarz](mailto:contact@micschwarz.dev) | wsl: add German translation (#7263) | 2021-11-02T16:40:33 | [381ba1d1689a](https://github.com/tldr-pages/tldr/commit/381ba1d1689af43dc3f22f916a369ff7aa078ba5)

