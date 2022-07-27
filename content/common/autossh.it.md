---
author: ['Marco Bonelli', 'bl-ue', 'marchersimon']
date: 1633112881
title: "autossh, TLDR Pages"
description: "autossh, Esegue, monitora e riavvia connessioni SSH."
categories: "common"
---
> Si riconnette automaticamente per tenere attivi tunnel di port forwarding. Accetta tutte le flag di ssh.

> Maggiori informazioni: <https://www.harding.motd.ca/autossh>.

- Apri una sessione SSH, riavviandola quando una porta monitorata smette di rispondere:

```bash
autossh -M porta_monitorata comando_ssh
```

- Apri una sessione ssh che forwarda una porta locale verso una remota, riavviandola se necessario:

```bash
autossh -M porta_monitorata -L porta_locale:localhost:porta_remota utente@host
```

- Forka prima di eseguire il comando ssh (si avvia in background) e non aprire una shell remota:

```bash
autossh -f -M porta_monitorata -N comando_ssh
```

- Esegui autossh in background, senza una porta da monitorare, utilizzando i keep-alive di SSH ogni 10 secondi per rilevare una disconnessione:

```bash
autossh -f -M 0 -N -o "ServerAliveInterval 10" -o "ServerAliveCountMax 3" comando_ssh
```

- Esegui autossh in background, senza una porta da monitorare, senza una shell remota, uscendo se il port forwarding fallisce:

```bash
autossh -f -M 0 -N -o "ServerAliveInterval 10" -o "ServerAliveCountMax 3" -o ExitOnForwardFailure=yes -L porta_locale:localhost:porta_remota utente@host
```

- Esegui autossh in background con output di debug su un file e output verboso di ssh su un altro file:

```bash
AUTOSSH_DEBUG=1 AUTOSSH_LOGFILE=file_log autossh -f -M porta_monitorata -v -E file_log_ssh comando_ssh
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | autossh: add Italian translation. | 2019-01-28T19:10:19 | [45a2401cdca7](https://github.com/tldr-pages/tldr/commit/45a2401cdca705b0aa9b340c90511e32558e534a)

