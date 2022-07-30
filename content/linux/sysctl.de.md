---
author: ['Kasjan Chilarski', 'Azrael JD']
date: 1643292617
title: "sysctl"
description: "sysctl, Laufzeit-Kernelparameter auflisten und ändern."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/sysctl.8>.

- Liste alle verfügbaren Kernelparameter mit ihren Werten auf:

```bash
sysctl -a
```

- Setze einen veränderbaren Kernelparameter:

```bash
sysctl -w sektion.tunable=wert
```

- Frage aktuell geöffnete Datei-Handler ab:

```bash
sysctl fs.file-nr
```

- Frage die maximale Anzahl geöffneter Dateien ab:

```bash
sysctl fs.file-max
```

- Übernimm Änderungen aus der `/etc/sysctl.conf` Datei:

```bash
sysctl -p
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Azrael JD](mailto:94840719+azraeljd@users.noreply.github.com) | sysctl: add more information link (#7718) | 2022-01-27T15:10:17 | [c837506fd7c3](https://github.com/tldr-pages/tldr/commit/c837506fd7c335137e6a42ceebe3a6eb3061caaa)
[Kasjan Chilarski](mailto:keistzen@gmail.com) | sysctl: add German translation (#6683) | 2021-10-03T23:08:21 | [7adcfdadeb05](https://github.com/tldr-pages/tldr/commit/7adcfdadeb057522aaec84a48e5115dc5aa85782)

