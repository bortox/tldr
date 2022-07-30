---
author: ['Nicolas Kosinski', 'Daniel', 'marchersimon']
date: 1634914980
title: "curl"
description: "curl, Überträgt Daten von oder zu einem Server."
categories: "common"
---
> Unterstützt die meisten Protokolle, inklusive HTTP, FTP und POP3.

> Weitere Informationen: <https://curl.se>.

- Lade den Inhalt einer URL in eine Datei:

```bash
curl http://beispiel.de --output pfad/zu/datei
```

- Lade eine Datei von einer URL herunter:

```bash
curl --remote-name http://beispiel.de/datei
```

- Lade eine Datei herunter, folge Weiterleitungen und setze vergangene Dateitransfers automatisch fort:

```bash
curl --remote-name --location --continue-at - http://beispiel.de/datei
```

- Sende formular-codierte Daten (POST Anfragen des Typs `application/x-www-form-urlencoded`). Benutze `--data @dateiname` oder `--data @'-'`, um von STDIN zu lesen:

```bash
curl --data 'name=karl-dieter' http://beispiel.de/formular
```

- Sende eine Anfrage mit einem extra Header mit einer eigenen HTTP-Methode:

```bash
curl --header 'X-Mein-Header: 123' --request PUT http://beispiel.de
```

- Sende Daten im JSON-Format und lege den geeigneten Inhaltstyp-Header fest:

```bash
curl --data '{"name":"karl-dieter"}' --header 'Content-Type: application/json' http://beispiel.de/benutzer/1234
```

- Übergib einen Benutzernamen und Passwort für die Server-Authentifizierung:

```bash
curl --user benutzername:passwort http://beispiel.de
```

- Übergib Client-Zertifikat und -Schlüssel für eine Ressource und überspringe die Zertifikatsüberprüfung:

```bash
curl --cert client.pem --key key.pem --insecure https://beispiel.de
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | curl: use long arguments (#5872) | 2021-05-04T11:37:07 | [69f02b651045](https://github.com/tldr-pages/tldr/commit/69f02b65104530e9f5d1d32a9528f2d3803050e0)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)

