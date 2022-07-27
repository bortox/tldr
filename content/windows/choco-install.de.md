---
author: ['Lucas Gabriel Schneider', 'LukBukkit', 'marchersimon']
date: 1619262596
title: "choco install, TLDR Pages"
description: "choco install, Installiere ein oder mehrere Pakete mit Chocolatey."
categories: "windows"
---
> Weitere Informationen: <https://chocolatey.org/docs/commands-install>.

- Installiere ein oder mehrere Pakete, deren Namen mit Leerzeichen getrennt sind:

```bash
choco install paket1 paket2
```

- Installiere Pakete aus einer Konfigurationsdatei:

```bash
choco install pfad/zu/pakete.config
```

- Installiere Pakete aus einer `nuspec`- oder `nupkg`-Datei:

```bash
choco install pfad/zu/datei
```

- Installiere eine bestimmte Version eines Pakets:

```bash
choco install paket --version version
```

- Erlaube die gleichzeitige Installation mehrerer Versionen eines Pakets:

```bash
choco install paket --allow-multiple
```

- Stimme allen Fragen automatisch zu:

```bash
choco install paket --yes
```

- Gib eine eigene Quelle an, von der Paket-Informationen abgerufen werden:

```bash
choco install paket --source quell_url|alias
```

- Gib einen Benutzernamen und ein Passwort für die Authentifizierung an:

```bash
choco install paket --user benutzername --password passwort
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[LukBukkit](mailto:luk.bukkit@gmail.com) | choco-install: add German translation | 2020-10-13T00:10:19 | [240988d41960](https://github.com/tldr-pages/tldr/commit/240988d4196088be1eb7412b0ca7d10060537f88)

