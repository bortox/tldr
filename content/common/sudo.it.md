---
author: ['mxmxyz', 'marchersimon']
date: 1633112881
title: "sudo"
description: "sudo, Esegue un singolo comando come superuser o come un altro utente."
categories: "common"
---
> Maggiori informazioni: <https://www.sudo.ws/sudo.html>.

- Esegui un comando come superuser:

```bash
sudo less /var/log/syslog
```

- Modifica un file come superuser con il tuo editor di default:

```bash
sudo -e /etc/fstab
```

- Esegui un comando come un altro utente e/o gruppo:

```bash
sudo -u utente -g gruppo id -a
```

- Ripeti l'ultimo comando prefissandolo con "sudo" (funziona solo in bash, zsh, ecc):

```bash
sudo !!
```

- Fai partire la shell di default con i privilegi da superuser:

```bash
sudo -i
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[mxmxyz](mailto:mxmxyzgxyzt@gmail.com) | 6 translations to italian | 2020-09-09T02:42:53 | [ae3ba00236f1](https://github.com/tldr-pages/tldr/commit/ae3ba00236f1e305ae16d0a317d345bffe88c857)

