---
author: ['Tommaso', 'bl-ue', 'marchersimon']
date: 1633112881
title: "cmd, TLDR Pages"
description: "cmd, L'interprete dei comandi di Windows."
categories: "windows"
---
> Maggiori informazioni: <https://docs.microsoft.com/windows-server/administration/windows-commands/cmd>.

- Lancia una nuova istanza dell'interprete dei comandi:

```bash
cmd
```

- Esegue il comando specificato e poi esce:

```bash
cmd /c "comando"
```

- Esegue il comando specificato e poi apre una shell interattiva:

```bash
cmd /k "comando"
```

- Disabilita l'uso di `echo` nell'output di un comando:

```bash
cmd /q
```

- Abilita o disabilita le estensioni ai comandi:

```bash
cmd /e:on|off
```

- Abilita o disabilita l'autocompletamento dei nomi di file e cartelle:

```bash
cmd /f:on|off
```

- Abilita o disabilita l'espansione delle variabili d'ambiente:

```bash
cmd /v:on|off
```

- Forza l'encoding delle stringhe in Unicode per l'output:

```bash
cmd /u
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Tommaso](mailto:p.tommy93@gmail.com) | cmd: add Italian translation (#4776) | 2020-10-24T14:17:48 | [831459e7ef2b](https://github.com/tldr-pages/tldr/commit/831459e7ef2b9724373dfb6495c94f1c1a2846d9)

