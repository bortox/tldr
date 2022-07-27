---
author: ['Leandro Meleti']
date: 1633378208
title: "arch-chroot, TLDR Pages"
description: "arch-chroot, Erweiterter `chroot`-Befehl zur Unterstützung des Arch Linux-Installationsprozesses."
categories: "linux"
---
> Weitere Informationen: <https://man.archlinux.org/man/arch-chroot.8>.

- Starte eine interaktive Shell (Standardmäßig `bash`) in einem neuen Root-Verzeichnis:

```bash
arch-chroot pfad/zu/neuem/root
```

- Spezifiziere den Benutzer (nicht der jetzige Benutzer) der die Shell ausführt:

```bash
arch-chroot -u anderer_benutzer pfad/zu/neuem/root
```

- Führe einen benutzerdefinierten Befehl (anstelle des Standardbefehls `bash`) im neuen Root-Verzeichnis aus:

```bash
arch-chroot pfad/zu/neuem/root befehl befehlsparameter
```

- Gib die Shell an, die nicht die Standard-Shell `bash` ist (in diesem Fall sollte das Paket `zsh` auf dem Zielsystem installiert worden sein):

```bash
arch-chroot pfad/zu/neuem/root zsh
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Leandro Meleti](mailto:leandromeleti97@hotmail.com) | arch-chroot: add German translation (#6789) | 2021-10-04T22:10:08 | [13d0ef4cf407](https://github.com/tldr-pages/tldr/commit/13d0ef4cf407f5aefd9c48efd2fa7d9d0199c95f)

