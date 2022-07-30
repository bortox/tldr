---
author: ['bl-ue', 'Felix Brilej', 'Daniel', 'marchersimon']
date: 1634914980
title: "aws quicksight"
description: "aws quicksight, CLI für AWS QuickSight."
categories: "common"
---
> Weitere Informationen: <https://docs.aws.amazon.com/cli/latest/reference/quicksight/>.

- Liste alle Datensätze auf:

```bash
aws quicksight list-data-sets --aws-account-id aws_account_id
```

- Liste alle Benutzer auf:

```bash
aws quicksight list-users --aws-account-id aws_account_id --namespace default
```

- Liste alle Gruppen auf:

```bash
aws quicksight list-groups --aws-account-id aws_account_id --namespace default
```

- Liste alle Dashboards auf:

```bash
aws quicksight list-dashboards --aws-account-id aws_account_id
```

- Liste einen Datensatz detailliert aus:

```bash
aws quicksight describe-data-set --aws-account-id aws_account_id --data-set-id datensatz_id
```

- Liste Zugangsberechtigungen zu einem Datensatz auf:

```bash
aws quicksight describe-data-set-permissions --aws-account-id aws_account_id --data-set-id datensatz_id
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:71837281+darmiel@users.noreply.github.com) | pages.de/*: fix spelling and grammar (#7135) | 2021-10-22T17:03:00 | [afe2deb899df](https://github.com/tldr-pages/tldr/commit/afe2deb899df7f1b3252bdd1326e56988568acce)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | German pages: replace `Mehr Informationen` with `Weitere Informationen` (#5814) | 2021-04-24T13:09:56 | [0a15df6ce3d7](https://github.com/tldr-pages/tldr/commit/0a15df6ce3d790b71b8fa4ae2e8befe0ed0806c7)
[marchersimon](mailto:marchersimon@zohomail.eu) | also include translated pages | 2021-04-11T17:29:10 | [4503438355cb](https://github.com/tldr-pages/tldr/commit/4503438355cb59acce6250c86fe756a89f0f334c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: clean up and normalize (#5437) | 2021-03-25T17:42:04 | [de311e174960](https://github.com/tldr-pages/tldr/commit/de311e17496083a7f805793ef228995ecc7e8c97)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Felix Brilej](mailto:11775168+flyck@users.noreply.github.com) | aws*: add German translation (#4827) | 2020-10-24T15:27:02 | [455f988c81a2](https://github.com/tldr-pages/tldr/commit/455f988c81a21f9d47983d5b1607d3d03b216db4)

