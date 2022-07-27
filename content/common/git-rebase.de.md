---
author: ['Kolja Markwardt']
date: 1637057830
title: "git rebase, TLDR Pages"
description: "git rebase, Wende Commits von einem Branch auf einen anderen Branch an."
categories: "common"
---
> Die Änderungen eines Branches werden auf einen bestehenden Branch "übertragen" und am Ende der Historie als neue Commits eingefügt.

> Weitere Informationen: <https://git-scm.com/docs/git-rebase>.

- Verwende einen anderen, angegebenen Branch als Basis für den aktuellen Branch:

```bash
git rebase neuer_basisbranch
```

- Starte einen interaktiven Rebase, bei dem Commits umsortiert, weggelassen, kombiniert oder verändert werden können:

```bash
git rebase -i ziel_basisbranch_oder_commithash
```

- Setze einen Rebase fort, der durch einen Mergefehler unterbrochen wurde, nachdem die Konflikte aufgelöst wurden:

```bash
git rebase --continue
```

- Setze einen Rebase fort, der durch einen Mergefehler unterbrochen wurde, durch Auslassen des in Konflikt stehenden Commits:

```bash
git rebase --skip
```

- Brich einen laufenden Rebase ab (z.B. wenn er durch Mergekonflikte unterbrochen wurde):

```bash
git rebase --abort
```

- Verschiebe einen Teil des aktuellen Branches auf eine neue Basis und gib die alte Basis an, ab der die Änderungen verwendet werden sollen:

```bash
git rebase --onto neue_basis alte_basis
```

- Bearbeite die 5 letzten Commits der aktuellen Basis um diese neu zu ordnen, auszulassen, kombinieren oder zu bearbeiten:

```bash
git rebase -i HEAD~5
```

- Löse Konflikte automatisch auf, indem der aktuelle Branch bevorzugt wird (das Schlüsselwort `theirs` hat in diesem Fall eine umgekehrte Bedeutung):

```bash
git rebase -X theirs branch_name
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Kolja Markwardt](mailto:kolja.markwardt@web.de) | git-rebase: add German translation (#7149) | 2021-11-16T11:17:10 | [3ae58b9d2061](https://github.com/tldr-pages/tldr/commit/3ae58b9d2061e0e5904539cc649b481e3ccf2d08)

