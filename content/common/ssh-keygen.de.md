---
author: ['Felix Brilej', 'syleung', 'Alexandru Duzsardi', 'Daniel', 'marchersimon']
date: 1634914980
title: "ssh-keygen"
description: "ssh-keygen, Generiert ssh Schlüssel für Authentifizierung, Passwort-lose Logins und mehr."
categories: "common"
---
> Weitere Informationen: <https://man.openbsd.org/ssh-keygen>.

- Erstelle ein SSH Schlüssel-Paar interaktiv:

```bash
ssh-keygen
```

- Erstelle ein Schlüssel-Paar unter einem bestimmten Dateinamen:

```bash
ssh-keygen -f ~/.ssh/datei
```

- Generiere ein ed25519 Schlüssel-Paar mit 100 Schlüssel-Ableitungs-Iterationen:

```bash
ssh-keygen -t ed25519 -a 100
```

- Generiere ein 4096 Bit langen RSA Schlüssel-Paar mit der E-Mail im Kommentarfeld:

```bash
ssh-keygen -t dsa|ecdsa|ed25519|rsa -b 4096 -C "kommentar|e-mail"
```

- Entferne den Schlüssel eines Servers aus der `known_hosts` Datei (hilfreich wenn ein Server seinen Schlüssel aktualisiert hat und der alte somit nicht mehr gilt):

```bash
ssh-keygen -R externer_server
```

- Rufe den Fingerabdruck eines Schlüssels im MD5 Hex Format ab:

```bash
ssh-keygen -l -E md5 -f ~/.ssh/datei
```

- Ändere das Passwort eines privaten Schlüssels:

```bash
ssh-keygen -p -f ~/.ssh/datei
```

- Ändern Sie den Typ des Schlüsselformats (z. B. vom OPENSSH-Format in PEM), die Datei wird an Ort und Stelle neu geschrieben:

```bash
ssh-keygen -p -N "" -m PEM -f ~/.ssh/datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[syleung](mailto:syleung@users.noreply.github.com) | common/ssh*: add more information link (#6659) | 2021-10-04T14:39:50 | [a092be52d7de](https://github.com/tldr-pages/tldr/commit/a092be52d7ded26ec56154160c90900c6338e76d)
[Alexandru Duzsardi](mailto:aduzsardi@users.noreply.github.com) | ssh-keygen: add key format conversion (#6213) | 2021-08-17T20:03:15 | [2392183ef0f4](https://github.com/tldr-pages/tldr/commit/2392183ef0f4ad9668129409a8f5ba828f0f0ec1)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | ssh*: Add German translation (#4835) | 2020-10-28T19:28:11 | [8bd6dd5ffad1](https://github.com/tldr-pages/tldr/commit/8bd6dd5ffad1ed34653270c3ebbed2387c41beac)

