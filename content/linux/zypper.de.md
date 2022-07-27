---
author: ['Quang Tran']
date: 1635872062
title: "zypper, TLDR Pages"
description: "zypper, SUSE & openSUSE Package-Management-Werkzeug."
categories: "linux"
---
> Weitere Informationen: <https://en.opensuse.org/SDB:Zypper_manual>.

- Synchronisiere die Liste von Paketen und verfügbaren Versionen:

```bash
zypper refresh
```

- Installiere ein neues Paket:

```bash
zypper install paket
```

- Entferne ein Paket:

```bash
zypper remove paket
```

- Aktualisiere installierte Pakete zur neuesten verfügbaren Version:

```bash
zypper update
```

- Suche Paket nach einem bestimmten Schema:

```bash
zypper search schema
```

- Zeige Informationen bezüglich der konfigurierten Repositories:

```bash
zypper repos --sort-by-priority
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Quang Tran](mailto:quangtran@mailbox.org) | zypper: add German translation (#7352) | 2021-11-02T17:54:22 | [77c184b38806](https://github.com/tldr-pages/tldr/commit/77c184b388069fb38bfd8cb823d619a3e4816fb1)

