---
author: ['bl-ue', 'Lucas Gabriel Schneider', 'profileid', 'marchersimon']
date: 1631521281
title: "ansible"
description: "ansible, Verwalte Computergruppen per Fernzugriff über SSH (Verwende die Datei `/etc/ansible/hosts`, um neue Gruppen/Hosts hinzuzufügen)."
categories: "common"
---
> Manche Unterbefehle wie `ansible galaxy` sind separat dokumentiert.

> Weitere Informationen: <https://www.ansible.com/>.

- Liste Hosts auf, die zu einer Gruppe gehören:

```bash
ansible gruppe --list-hosts
```

- Pinge eine Gruppe von Hosts an:

```bash
ansible gruppe -m ping
```

- Zeige Informationen über eine Gruppe von Hosts an:

```bash
ansible gruppe -m setup
```

- Führe einen Befehl auf einer Gruppe von Hosts aus:

```bash
ansible gruppe -m command -a 'befehl'
```

- Führe einen Befehl mit administrativen Privilegien aus:

```bash
ansible gruppe --become --ask-become-pass -m command -a 'befehl'
```

- Führe einen Befehl mit einer benutzerdefinierten Inventardatei aus:

```bash
ansible Gruppe -i inventardatei -m command -a 'befehl'
```

- Liste alle Gruppen eines Inventars auf:

```bash
ansible localhost -m debug -a 'var=groups.keys()'
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: refresh outdated translations (#5839) | 2021-05-01T20:20:15 | [348fbed93786](https://github.com/tldr-pages/tldr/commit/348fbed937865e33794197c0838aa2939abd41bc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[profileid](mailto:40308458+ProfileID@users.noreply.github.com) | ansible: add German translation | 2020-10-02T21:12:31 | [915a54bd2000](https://github.com/tldr-pages/tldr/commit/915a54bd2000fb2209a4c42b11e9d61ba3045a65)

