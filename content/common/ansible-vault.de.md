---
author: ['Florian', 'Daniel', 'marchersimon']
date: 1634914980
title: "ansible-vault"
description: "ansible-vault, Verschlüsselt und entschlüsselt Werte, Datenstrukturen und Dateien innerhalb von Ansible-Projekten."
categories: "common"
---
> Weitere Informationen: <https://docs.ansible.com/ansible/latest/user_guide/vault.html#id17>.

- Erstelle eine neue verschlüsselte Vault-Datei mit einer Eingabeaufforderung für ein Passwort:

```bash
ansible-vault create vault_datei
```

- Erstelle eine neue verschlüsselte Vault-Datei mit einer Vault-Schlüsseldatei, um sie zu verschlüsseln:

```bash
ansible-vault create --vault-password-file=schlüsseldatei vault_datei
```

- Verschlüssle eine vorhandene Datei mit einer optionalen Schlüsseldatei:

```bash
ansible-vault encrypt --vault-password-file=schlüsseldatei vault_file
```

- Verschlüssle eine Zeichenfolge mit dem verschlüsselten Zeichenfolgenformat von Ansible, wobei interaktive Eingabeaufforderungen angezeigt werden:

```bash
ansible-vault encrypt_string
```

- Zeige eine verschlüsselte Datei an, wobei eine Kennwortdatei zum Entschlüsseln verwendet wird:

```bash
ansible-vault view --vault-password-file=schlüsseldatei vault_datei
```

- Verschlüssle eine bereits verschlüsselte Vault Datei mit einer neuen Kennwortdatei neu:

```bash
ansible-vault rekey --vault-password-file=alte_schlüsseldatei --new-vault-password-file=neue_schlüsseldatei vault_datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[Florian](mailto:40308458+ProfileID@users.noreply.github.com) | 7z, ansible-playbook, ansible-vault, plantuml: add german translation (#4234) | 2020-08-02T20:47:28 | [bb6f6dbe3793](https://github.com/tldr-pages/tldr/commit/bb6f6dbe37937d552739f11596e75918a49d9356)

