---
author: ['LukBukkit', 'marchersimon']
date: 1619262596
title: "git remote"
description: "git remote, Verwalte eine gewisse Anzahl an Repositories (remotes)."
categories: "common"
---
> Weitere Informationen: <https://git-scm.com/docs/git-remote>.

- Liste alle existierenden Remotes, ihre Namen und ihre URLs auf:

```bash
git remote -v
```

- Zeige Informationen über ein Remote an:

```bash
git remote show remote_name
```

- Füge ein neues Remote hinzu:

```bash
git remote add remote_name remote_url
```

- Ändere die URL eines Remotes (benutze `--add` um die existierende URL zu behalten):

```bash
git remote set-url remote_name remote_url
```

- Entferne ein Remote:

```bash
git remote remove remote_name
```

- Benenne ein Remote um:

```bash
git remote rename alter_name neuer_name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[LukBukkit](mailto:luk.bukkit@gmail.com) | git-remote: add German translation | 2020-10-24T14:39:05 | [72cc045baab9](https://github.com/tldr-pages/tldr/commit/72cc045baab9d0d2e38d6da723631ccc02852449)

