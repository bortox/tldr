---
author: ['Kasjan Chilarski', 'Daniel']
date: 1634914980
title: "df"
description: "df, Verschafft einen Überblick über verfügbaren Speicherplatz im Dateisystem."
categories: "common"
---
> Weitere Informationen: <https://www.gnu.org/software/coreutils/df>.

- Zeige verfügbaren Platz auf allen eingehängten Dateisystemen:

```bash
df
```

- Zeige verfügbaren Platz auf allen eingehängten Dateisystemen in einem menschenlesbaren Format:

```bash
df -h
```

- Zeige das Dateisystem und dessen Speicherverbrauch, das die angegebene Datei oder Verzeichnis enthält:

```bash
df pfad/zu/datei_oder_verzeichnis
```

- Zeige Statistiken über die Anzahl freier Inodes:

```bash
df -i
```

- Zeige alle Dateisysteme bis auf die eines bestimmten Typs:

```bash
df -x squashfs -x tmpfs
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[Kasjan Chilarski](mailto:keistzen@gmail.com) | df: add German translation (#6696) | 2021-10-03T15:19:02 | [4a7e804464de](https://github.com/tldr-pages/tldr/commit/4a7e804464debf7af498a97e2be654130848c559)

