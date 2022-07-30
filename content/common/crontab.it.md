---
author: ['Marco Bonelli', 'marchersimon']
date: 1659075216
title: "crontab"
description: "crontab, Programma cron job per essere eseguiti a determinati intervalli di tempo per l'utente corrente."
categories: "common"
---
> Formato definizione di un job: "(minuto) (ora) (giorno_del_mese) (mese) (giorno_della_settimana) comando_da_eseguire".

> Maggiori informazioni: <https://crontab.guru/>.

- Modifica il file crontab per l'utente corrente:

```bash
crontab -e
```

- Elenca i cron job esistenti per l'utente corrente:

```bash
crontab -l
```

- Rimuovi tutti i cron job per l'utente corrente:

```bash
crontab -r
```

- Esempio di un job eseguito alle 10:00 ogni giorno (* vuol dire qualsiasi valore):

```bash
0 10 * * * comando_da_eseguire
```

- Esempio di un job eseguito ogni minuto il 3 Aprile:

```bash
* * 3 Apr * comando_da_eseguire
```

- Esempio di un job che esegue un determinato script alle 02:30 ogni venerdì:

```bash
30 2 * * Fri /percorso/assoluto/allo/script.sh
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-04-18T16:33:27 | [b607ecb4d79c](https://github.com/tldr-pages/tldr/commit/b607ecb4d79c009f43e017a58d2b5b797fdaf3bd)
[marchersimon](mailto:marchersimon@zohomail.eu) | crontab: add link | 2021-04-18T16:33:27 | [bd351f01b414](https://github.com/tldr-pages/tldr/commit/bd351f01b41415c6edd6b7b6c4e3c2051287f322)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | contab: add Italian translation. | 2019-06-10T01:35:02 | [3c42db7a476b](https://github.com/tldr-pages/tldr/commit/3c42db7a476bef5687683cadec22eb1f6924361a)

