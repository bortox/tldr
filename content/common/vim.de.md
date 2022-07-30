---
author: ['frhcheck24']
date: 1638555523
title: "vim"
description: "vim, Vim (Vi IMproved), ein Befehlszeilen-Texteditor, bietet mehrere Modi für verschiedene Arten der Textmanipulation an."
categories: "common"
---
> Das Drücken von `i` schaltet den Editier-Modus ein. `<Esc>` wechselt in den Befehls-Modus, der die Verwendung von Vim-Befehlen ermöglicht.

> Weitere Informationen: <https://www.vim.org>.

- Öffne eine Datei:

```bash
vim pfad/zu/datei
```

- Öffne eine Datei an einer bestimmten Zeilennummer:

```bash
vim +zeilennummer pfad/zu/datei
```

- Zeige Vim's Benutzeranleitung:

```bash
:help<Enter>
```

- Speichere und schließe die aktuelle Datei:

```bash
:wq<Enter>
```

- Mache die letzte Aktion rückgängig:

```bash
u
```

- Suche nach einem Muster in der Datei (mit `n`/`N` zum nächsten/vorherigen Treffer gehen):

```bash
/suchmuster<Enter>
```

- Ersetze einen regulären Ausdruck alle Treffer in einer Datei:

```bash
:%s/regulärer_ausdruck/neuer_text/g<Enter>
```

- Zeige Zeilennummern an:

```bash
:set nu<Enter>
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[frhcheck24](mailto:70907916+frhcheck24@users.noreply.github.com) | vim: add German translation (#7114) | 2021-12-03T19:18:43 | [1ff6ff663701](https://github.com/tldr-pages/tldr/commit/1ff6ff6637016200d5b33fde49f94500a07ac384)

