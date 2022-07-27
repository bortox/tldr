---
author: ['ruben-tura', 'Axel Navarro']
date: 1641649180
title: "a2query, TLDR Pages"
description: "a2query, Recupera la configurazione di runtime da Apache su sistemi operativi basati su Debian."
categories: "linux"
---
> Maggiori informazioni: <https://manpages.debian.org/latest/apache2/a2query.html>.

- Lista i moduli Apache attivi:

```bash
sudo a2query -m
```

- Controlla se un modulo specifico è installato:

```bash
sudo a2query -m nome_modulo
```

- Lista virtual host attivi:

```bash
sudo a2query -s
```

- Mostra il Modulo Multi-Processo correntemente attivo:

```bash
sudo a2query -M
```

- Mostra la versione di Apache:

```bash
sudo a2query -v
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | a2query, dpkg*, check-support-status, netselect-apt, reportbug: update Debian link (#7622) * a2query: update link to Debian manpage * [...] | 2022-01-08T14:39:40 | [84b6cabf6ef8](https://github.com/tldr-pages/tldr/commit/84b6cabf6ef870441744497edf1c184b8888d727)
[ruben-tura](mailto:64353994+ruben-tura@users.noreply.github.com) | hello, a2*: add Italian translation (#6867) | 2021-10-16T22:56:41 | [c276911c4d90](https://github.com/tldr-pages/tldr/commit/c276911c4d9087838e94a896d1733efdc3267bc2)

