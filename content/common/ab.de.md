---
author: ['bl-ue', 'marchersimon']
date: 1619262596
title: "ab"
description: "ab, Apache HTTP server Benchmarking Tool."
categories: "common"
---
> Weitere Informationen: <https://httpd.apache.org/docs/current/programs/ab.html>.

- Sende 100 HTTP GET Anfragen an eine URL:

```bash
ab -n 100 url
```

- Sende 100 HTTP GET Anfragen an eine URL, wovon bis zu 10 gleichzeitig bearbeitet werden:

```bash
ab -n 100 -c 10 url
```

- Wach halten:

```bash
ab -k url
```

- Lege die maximale Anzahl an Sekunden fest, die das Benchmarking dauern darf:

```bash
ab -t 60 url
```

- Sende 100 HTTP POST Anfragen an eine URL, wobei eine JSON Belastung aus einer Datei verwendet wird:

```bash
ab -n 100 -T application/json -p pfad/zu/datei.json url
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | ab: update grammar; update link (#5433) | 2021-03-13T22:44:59 | [8f2ed246f761](https://github.com/tldr-pages/tldr/commit/8f2ed246f7614df6e815b9eefae053a0f64df920)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)

