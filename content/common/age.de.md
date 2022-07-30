---
author: ['FantasyCookie17', 'marchersimon']
date: 1619262596
title: "age"
description: "age, Ein einfaches, modernes und sicheres Dateiverschlüsselungswerkzeug."
categories: "common"
---
> Weitere Informationen: <https://age-encryption.org>.

- Generiere eine verschlüsselte Datei, die mit einer Passphrase entschlüsselt werden kann:

```bash
age --passphrase --output pfad/zu/verschlüsselter_datei pfad/zu/unverschlüsselter_datei
```

- Generiere ein Schlüsselpaar, speichere dabei den privaten Schlüssel in einer unverschlüsselten Datei und gib den öffentlichen Schlüssel zu stdout aus:

```bash
age-keygen --output pfad/zu/datei
```

- Verschlüssle eine Datei mit einem oder mehr öffentlichen Schlüsseln, die als Zeichenketten eingegeben werden:

```bash
age --recipient öffentlicher_schlüssel_1 --recipient öffentlicher_schlüssel_2 pfad/zu/unverschlüsselter_datei --output pfad/zu/verschlüsselter_datei
```

- Verschlüssle eine Datei mit einem oder mehr öffentlichen Schlüsseln, die in einer Empfängerdatei angegeben sind:

```bash
age --recipients-file pfad/zu/empfängerdatei pfad/zu/unverschlüsselter_datei --output pfad/zu/verschlüsselter_datei
```

- Entschlüssle eine Datei mit einer Passphrase:

```bash
age --decrypt --output pfad/zu/entschlüsselter_datei pfad/zu/verschlüsselter_datei
```

- Entschlüssle eine Datei mit einer privaten Schlüsseldatei:

```bash
age --decrypt --identity pfad/zu/privater_schlüsseldatei --output pfad/zu/entschlüsselter_datei pfad/zu/verschlüsselter_datei
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[FantasyCookie17](mailto:fantasycookie17@artemislena.eu) | age: add page (#5758) | 2021-04-20T02:14:13 | [f5469ee92cbd](https://github.com/tldr-pages/tldr/commit/f5469ee92cbde6827bad858b6709c8d9a5d50c08)

