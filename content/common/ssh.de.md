---
author: ['Felix Brilej', 'Daniel', 'Phil Enzler', 'lincc', 'Nicolai Weitkemper', 'bl-ue', 'marchersimon']
date: 1636372515
title: "ssh, TLDR Pages"
description: "ssh, Secure Shell ist ein Protokoll für das sichere einloggen auf einem externen System."
categories: "common"
---
> Es kann dafür eingesetzt werden um Befehle auf externen Systemen auszuführen.

> Weitere Informationen: <https://man.openbsd.org/ssh>.

- Stelle eine Verbindung zu einem externen Server her:

```bash
ssh benutzer@externer_server
```

- Stelle eine Verbindung zu einem externen Server mit spezifischer Identität her (privater SSH Schlüssel):

```bash
ssh -i pfad/zu/schlüssel_datei benutzer@externer_server
```

- Stelle eine Verbindung zu einem externen Server unter einem spezifischen Port her:

```bash
ssh benutzer@externer_server -p 2222
```

- Führen einen Befehl auf einem externen Server aus:

```bash
ssh externer_server befehl
```

- SSH Tunneln: Leite Ports dynamische Port weiter (SOCKS proxy auf localhost:1080):

```bash
ssh -D 1080 benutzer@externer_server
```

- SSH Tunneln: Leite einen spezifischen Ports (localhost:9999 zu example.org:80) weiter zusammen mit deaktivierter pseudy-tty Provisionierung für die Ausführung eines Befehls:

```bash
ssh -L 9999:example.org:80 -N -T benutzer@externer_server
```

- SSH Springen: Verbinde über einen Spring-Server zu einem externen Server (Es können auch mehrere Spring-Server über eine Komma-separierte Liste angegeben werden):

```bash
ssh -J benutzer@sring_server benutzer@externer_server
```

- Agenten Weiterleitung: Leite die eigenen Authentifizierungs-Information an den externen Server weiter (siehe `man ssh_config` für mehr Optionen):

```bash
ssh -A benutzer@externer_server
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[Nicolai Weitkemper](mailto:nico.weio@gmail.com) | ssh: fix typo in German translation (#6453) | 2021-09-02T14:13:53 | [b4a18d95addd](https://github.com/tldr-pages/tldr/commit/b4a18d95adddc53b37e2dd2f10efa0ea160285be)
[Phil Enzler](mailto:phil@pushbutton.studio) | ssh: remove -C and use SOCKS port (#5771) | 2021-04-16T03:47:49 | [38c3b011dc62](https://github.com/tldr-pages/tldr/commit/38c3b011dc62cb45b7c2df5708bd3a6a02ec0fe3)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | ssh*: Add German translation (#4835) | 2020-10-28T19:28:11 | [8bd6dd5ffad1](https://github.com/tldr-pages/tldr/commit/8bd6dd5ffad1ed34653270c3ebbed2387c41beac)

