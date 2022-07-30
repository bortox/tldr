---
author: ['LukBukkit', 'marchersimon']
date: 1626631245
title: "git clone"
description: "git clone, Klone ein existierendes Repository."
categories: "common"
---
> Weitere Informationen: <https://git-scm.com/docs/git-clone>.

- Klone ein existierendes Repository:

```bash
git clone url_zu_repository
```

- Klone ein existierendes Repository in ein bestimmtes Verzeichnis:

```bash
git clone url_zu_repository pfad/zu/verzeichnis
```

- Klone ein existierendes Repository und seine Submodule:

```bash
git clone --recursive url_zu_repository
```

- Klone ein lokales Repository:

```bash
git clone -l pfad/zu/lokalem_repository
```

- Klone ohne Meldungen:

```bash
git clone -q url_zu_repository
```

- Klone ein existierendes Repository und rufe nur die neuesten 10 Commits im Standard-Branch ab (spart Zeit):

```bash
git clone --depth 10 url_zu_repository
```

- Klone ein existierendes Repository, aber lade nur einen bestimmten Branch herunter:

```bash
git clone --branch name --single-branch url_zu_repository
```

- Klone ein existierendes Repository mit einem bestimmten SSH Befehl:

```bash
git clone --config core.sshCommand="ssh -i pfad/zu/privat_ssh_schlüssel" url_zu_repository
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, ansible-galaxy, convert, dd, exa, fuck, git-*, gpg, ls, mv: sync German page (#6226) | 2021-07-18T20:00:45 | [1dcdac60df90](https://github.com/tldr-pages/tldr/commit/1dcdac60df901488a051d3f2f2e4171a158be904)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: refresh outdated translations (#5839) | 2021-05-01T20:20:15 | [348fbed93786](https://github.com/tldr-pages/tldr/commit/348fbed937865e33794197c0838aa2939abd41bc)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[LukBukkit](mailto:luk.bukkit@gmail.com) | git-clone: add German translation | 2020-10-24T14:39:05 | [34d67d975f8c](https://github.com/tldr-pages/tldr/commit/34d67d975f8c54a38b2968b98a7d768ff076a022)

