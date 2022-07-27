---
author: ['Kasjan Chilarski', 'Jimmy']
date: 1633450842
title: "mount, TLDR Pages"
description: "mount, Ermöglicht den Zugriff auf ein gesamtes Dateisystem in einem Verzeichnis."
categories: "common"
---
> Weitere Informationen: <https://manned.org/mount.8>.

- Zeige alle eingehängten Dateisyteme:

```bash
mount
```

- Hänge ein Gerät in ein Verzeichnis ein:

```bash
mount -t dateisystemtyp pfad/zu/gerätedatei pfad/zu/zielverzeichnis
```

- Hänge ein CD-ROM-Gerät (Dateisystemtyp ISO9660) in das Verzeichnis `/cdrom` schreibgeschützt ein:

```bash
mount -t iso9660 -o ro /dev/cdrom /cdrom
```

- Hänge alle Dateisysteme ein, die in `/etc/fstab` definiert sind:

```bash
mount -a
```

- Hänge ein Dateisystem ein, das in `/etc/fstab` beschrieben ist (z. B. `/dev/sda1 /meine_platte ext2 defaults 0 2`):

```bash
mount /meine_platte
```

- Hänge ein Verzeichnis in ein anderes Verzeichnis ein (danach sind die Inhalte über beide Pfade verfügbar):

```bash
mount --bind pfad/zu/altem_verzeichnis pfad/zu/neuem_verzeichnis
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Jimmy](mailto:30603522+jim4067@users.noreply.github.com) | mount: add more information link (#6788) | 2021-10-05T18:20:42 | [96bb5fde4169](https://github.com/tldr-pages/tldr/commit/96bb5fde416932e736be172e2de8be432596aaee)
[Kasjan Chilarski](mailto:keistzen@gmail.com) | mount: add German translation (#6698) | 2021-10-04T14:34:59 | [527993580ebc](https://github.com/tldr-pages/tldr/commit/527993580ebc87635a26971118d4717f3a36ec03)

