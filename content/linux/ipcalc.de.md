---
author: ['3ncy']
date: 1635847027
title: "ipcalc, TLDR Pages"
description: "ipcalc, Einfache Operationen und Berechnungen mit IP-Adressen und Netzwerken durchführen."
categories: "linux"
---
> Weitere Informationen: <https://manned.org/ipcalc>.

- Zeige Informationen über eine Adresse oder ein Netzwerk mit einer bestimmten Subnetzmaske an:

```bash
ipcalc 1.2.3.4 255.255.255.0
```

- Zeige Informationen über eine Adresse oder ein Netzwerk in CIDR-Notation an:

```bash
ipcalc 1.2.3.4/24
```

- Zeige die Broadcast-Adresse einer Adresse oder eines Netzwerks an:

```bash
ipcalc -b 1.2.3.4/30
```

- Zeige die Netzwerkadresse der angegebenen IP-Adresse und Netzmaske an:

```bash
ipcalc -n 1.2.3.4/24
```

- Zeige geografische Informationen zu einer bestimmten IP-Adresse an:

```bash
ipcalc -g 1.2.3.4
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[3ncy](mailto:53367954+3ncy@users.noreply.github.com) | google-chrome, ipcalc, nologin, ...: add German translation (#7290) | 2021-11-02T10:57:07 | [c45572ce7377](https://github.com/tldr-pages/tldr/commit/c45572ce7377dffa45e0791c419a6f17af40865a)

