---
author: ['Frank Benedikt', 'bl-ue', 'marchersimon']
date: 1619262596
title: "alias"
description: "alias, Erstellt Aliasse - Alterative Namen für Befehle."
categories: "common"
---
> Aliasse laufen mit der aktuellen Shell-Sitzung ab, es sei denn, sie werden in der Konfigurationsdatei der Shell definiert, z.B. `~/.bashrc`.

> Weitere Informationen: <https://tldp.org/LDP/abs/html/aliases.html>.

- Listet alle Aliasse auf:

```bash
alias
```

- Erstellt einen Alias:

```bash
alias alias="befehl"
```

- Zeigt den mit einem bestimmten Alias verknüpften Befehl an:

```bash
alias alias
```

- Entferne einen Alias:

```bash
unalias alias
```

- Macht `rm` zu einem interaktiven Befehl:

```bash
alias rm="rm -i"
```

- Erstellt den Alias `la` für `ls -a`:

```bash
alias la="ls -a"
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | alias: add more information link (#5644) | 2021-03-30T20:57:29 | [edd9c5a5dc32](https://github.com/tldr-pages/tldr/commit/edd9c5a5dc32839ecf45b50d02d0260b8032002e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Frank Benedikt](mailto:63481435+FrankBG67@users.noreply.github.com) | German translation: alias, bash, borg, cd, chmod, chromium, chsh, convert, exa (#4132) Co-authored-by: Zlatan Vasović [...] | 2020-06-29T23:59:34 | [9aa5907281cb](https://github.com/tldr-pages/tldr/commit/9aa5907281cbaa7a0ee08b5c330c660d779282c7)

