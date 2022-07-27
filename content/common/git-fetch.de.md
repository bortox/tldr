---
author: ['FantasyCookie17', 'LukBukkit', 'marchersimon']
date: 1619600234
title: "git fetch, TLDR Pages"
description: "git fetch, Lade Objekte und Referenzen (refs) von einem entfernten Repository."
categories: "common"
---
> Weitere Informationen: <https://git-scm.com/docs/git-fetch>.

- Hole die neuesten Änderungen von dem standardmäßigen Repository im Upstream (wenn gesetzt):

```bash
git fetch
```

- Hole neue Branches von einem bestimmten Repository im Upstream:

```bash
git fetch name_des_upstream_repository
```

- Hole die neuesten Änderungen von allen Repositories im Upstream:

```bash
git fetch --all
```

- Lade auch die Tags des Repository im Upstream:

```bash
git fetch --tags
```

- Lösche lokale Referenzen auf entfernte Branches, die im Upstream-Repository nicht mehr existieren:

```bash
git fetch --prune
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[FantasyCookie17](mailto:fantasycookie17@artemislena.eu) | German pages: Change 'neuste' to 'neueste' (#5844) | 2021-04-28T10:57:14 | [48b7458c8559](https://github.com/tldr-pages/tldr/commit/48b7458c85594857653369e5e9941fe3961c79f0)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[LukBukkit](mailto:luk.bukkit@gmail.com) | git-fetch: add German translation | 2020-10-24T14:39:05 | [9113621979ff](https://github.com/tldr-pages/tldr/commit/9113621979fff391e57034ef40cc2af62b83f032)

