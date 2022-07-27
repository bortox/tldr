---
author: ['Leandro Meleti']
date: 1633333621
title: "adduser, TLDR Pages"
description: "adduser, Tool um Benutzer hinzuzufügen."
categories: "linux"
---
> Weitere Informationen: <https://manpages.debian.org/latest/adduser/adduser.html>.

- Erstelle einen neuen Benutzer mit einem Standard-Home-Verzeichnis und Aufforderung an den Benutzer, ein Passwort festzulegen:

```bash
adduser benutzername
```

- Erstelle einen neuen Benutzer ohne Home-Verzeichnis:

```bash
adduser --no-create-home benutzername
```

- Erstelle einen neuen Benutzer mit einem Home-Verzeichnis unter dem angegebenen Pfad:

```bash
adduser --home pfad/zu/home benutzername
```

- Erstelle einen neuen Benutzer, bei dem die angegebene Shell als Anmeldeshell eingestellt ist:

```bash
adduser --shell pfad/zu/shell benutzername
```

- Erstelle einen neuen Benutzer und füge ihn zur angegebenen Gruppe hinzu:

```bash
adduser --ingroup gruppe benutzername
```

- Füge einen vorhandenen Benutzer zur angegebenen Gruppe hinzu:

```bash
adduser benutzername gruppe
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Leandro Meleti](mailto:leandromeleti97@hotmail.com) | adduser: add German translation (#6690) | 2021-10-04T09:47:01 | [3f3d5e73d282](https://github.com/tldr-pages/tldr/commit/3f3d5e73d282695e694c8eaa54303d2ac59fdd28)

