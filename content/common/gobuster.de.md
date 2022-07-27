---
author: ['ollo-der-echte']
date: 1633613287
title: "gobuster, TLDR Pages"
description: "gobuster, Findet versteckte Pfade auf Webservern und mehr."
categories: "common"
---
> Weitere Informationen: <https://github.com/OJ/gobuster>.

- Finde Verzeichnisse und Dateien, die den Wörtern der Wortliste entsprechen.

```bash
gobuster dir --url https://beispiel.com/ --wordlist pfad/zu/datei
```

- Finde Subdomains:

```bash
gobuster dns --domain beispiel.com --wordlist pfad/zu/datei
```

- Finde Amazon S3-Buckets:

```bash
gobuster s3 --wordlist pfad/zu/datei
```

- Finde andere virtuelle Hosts eines Servers:

```bash
gobuster vhost --url https://beispiel.com/ --wordlist pfad/zu/datei
```

- Fuzze den Wert eines URL-Parameters:

```bash
gobuster fuzz --url https://beispiel.com/?parameter=FUZZ --wordlist pfad/zu/datei
```

- Fuzze den Namen eines URL-Parameters

```bash
gobuster fuzz --url https://beispiel.com/?FUZZ=wert --wordlist pfad/zu/datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[ollo-der-echte](mailto:83571465+ollo-der-echte@users.noreply.github.com) | gobuster: add German translation (#6786) | 2021-10-07T15:28:07 | [64135424aeaf](https://github.com/tldr-pages/tldr/commit/64135424aeaf253dacfd16e111a8cd533f4924e1)

