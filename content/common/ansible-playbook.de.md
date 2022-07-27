---
author: ['Florian', 'bl-ue', 'marchersimon']
date: 1619262596
title: "ansible-playbook, TLDR Pages"
description: "ansible-playbook, In Playbook definierte Aufgaben auf entfernten Rechnern über SSH ausführen."
categories: "common"
---
> Weitere Informationen: <https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html>.

- Führe Aufgaben im Playbook aus:

```bash
ansible-playbook playbook
```

- Führe Aufgaben im Playbook mit benutzerdefiniertem Host-Bestand aus:

```bash
ansible-playbook playbook -i inventory_datei
```

- Führe Aufgaben im Playbook aus, wobei zusätzliche Variablen über die Befehlszeile definiert werden:

```bash
ansible-playbook playbook -e "variable1=wert1 variable2=wert2"
```

- Führe Aufgaben in Playbook mit zusätzlichen Variablen aus, die in einer JSON-Datei definiert sind:

```bash
ansible-playbook playbook -e "@variablen.json"
```

- Führe Aufgaben im Playbook für die angegebenen Tags aus:

```bash
ansible-playbook playbook --tags tag1,tag2
```

- Führe Aufgaben in einem Playbook aus, die mit einer bestimmten Aufgabe beginnen:

```bash
ansible-playbook playbook --start-at aufgabenname
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Florian](mailto:40308458+ProfileID@users.noreply.github.com) | 7z, ansible-playbook, ansible-vault, plantuml: add german translation (#4234) | 2020-08-02T20:47:28 | [bb6f6dbe3793](https://github.com/tldr-pages/tldr/commit/bb6f6dbe37937d552739f11596e75918a49d9356)

