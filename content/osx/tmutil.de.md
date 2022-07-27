---
author: ['Kargins', 'marchersimon']
date: 1619262596
title: "tmutil, TLDR Pages"
description: "tmutil, Dienstprogramm zum Verwalten von Time Machine-Backups. Die meisten Befehle erfordern Root-Rechte."
categories: "osx"
---
> Weitere Informationen: <https://ss64.com/osx/tmutil.html>.

- Setze ein HFS+ Laufwerk als Backupziel:

```bash
sudo tmutil setdestination pfad/zu/einhänge_punkt
```

- Setze eine APF-Freigabe oder SMB-Freigabe als Backupziel:

```bash
sudo tmutil setdestination protocol://benutzer[:passwort]@host/share
```

- Hänge das angegebene Ziel an die Liste der Backupziele an:

```bash
sudo tmutil setdestination -a ziel
```

- Aktiviere automatische Backups:

```bash
sudo tmutil enable
```

- Deaktiviere automatische Backups:

```bash
sudo tmutil disable
```

- Starte ein Backup im Hintergrund, falls nicht bereits eines läuft:

```bash
sudo tmutil startbackup
```

- Starte ein Backup im Vordergrund, falls nicht bereits eines läuft:

```bash
sudo tmutil startbackup -b
```

- Stoppe ein laufendes Backup:

```bash
sudo tmutil stopbackup
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Kargins](mailto:GETandSELECT@users.noreply.github.com) | brew-bundle, caffeinate, open and tmutil: add German translation (#5178) * brew-bundle, caffeinate, open and tmutil: add German [...] | 2021-01-24T17:23:41 | [50cff8c9e6cc](https://github.com/tldr-pages/tldr/commit/50cff8c9e6ccb71814f52be4a517f8a07b51cd0f)

