---
author: ['Thomas Wünsche', 'Marco Bonelli', 'Kostyantyn Moroz', 'Agniva De Sarker', 'Peter Nguyen', 'CleanMachine1', 'Kocsen', 'marchersimon']
date: 1657380979
title: "crontab, TLDR Pages"
description: "crontab, Schedule cron jobs to run on a time interval for the current user."
categories: "common"
---
> More information: <https://crontab.guru/>.

- Edit the crontab file for the current user:

```bash
crontab -e
```

- Edit the crontab file for a specific user:

```bash
sudo crontab -e -u user
```

- Replace the current crontab with the contents of the given file:

```bash
crontab path/to/file
```

- View a list of existing cron jobs for current user:

```bash
crontab -l
```

- Remove all cron jobs for the current user:

```bash
crontab -r
```

- Sample job which runs at 10:00 every day (* means any value):

```bash
0 10 * * * command_to_execute
```

- Sample crontab entry, which runs a command every 10 minutes:

```bash
*/10 * * * * command_to_execute
```

- Sample crontab entry, which runs a certain script at 02:30 every Friday:

```bash
30 2 * * Fri /absolute/path/to/script.sh
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | crontab: refresh (#8182) | 2022-07-09T17:36:19 | [59a15bf3a527](https://github.com/tldr-pages/tldr/commit/59a15bf3a5278fbc1a83525c0030d201218ec49c)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-04-18T16:33:27 | [b607ecb4d79c](https://github.com/tldr-pages/tldr/commit/b607ecb4d79c009f43e017a58d2b5b797fdaf3bd)
[marchersimon](mailto:marchersimon@zohomail.eu) | crontab: add link | 2021-04-18T16:33:27 | [bd351f01b414](https://github.com/tldr-pages/tldr/commit/bd351f01b41415c6edd6b7b6c4e3c2051287f322)
[Thomas Wünsche](mailto:42999314+thomaswuensche@users.noreply.github.com) | crontab: add file example (#4958) | 2020-11-20T23:01:33 | [02bc8ffd90c7](https://github.com/tldr-pages/tldr/commit/02bc8ffd90c7b934242ff238e65b2591af7f4d21)
[Peter Nguyen](mailto:peter@mictis.com) | crontab: Add example of editing crontab for a user using the -u flag (#3178) | 2019-07-09T19:27:00 | [46023de9ddae](https://github.com/tldr-pages/tldr/commit/46023de9ddae744eb665fb64f48296a148560dfd)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | crontab: clarify and simplify job examples. (#2938) | 2019-04-22T18:28:30 | [d0677b83d27c](https://github.com/tldr-pages/tldr/commit/d0677b83d27c0960a3420a911fdea6459b0bddd5)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | cron: Use day/month names instead of nos. | 2016-09-09T09:52:41 | [835c4a3e49ca](https://github.com/tldr-pages/tldr/commit/835c4a3e49ca7d4597f57a86567ff2dbaae030af)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | cron: Add job definition example | 2016-09-08T11:39:19 | [3c00a0d18012](https://github.com/tldr-pages/tldr/commit/3c00a0d18012a7a03b8e55a5b7c2f9ab0c5304bd)
[Kostyantyn Moroz](mailto:koskokos@gmail.com) | Added format of crontab file | 2016-09-08T11:39:19 | [ace09a9c9b4b](https://github.com/tldr-pages/tldr/commit/ace09a9c9b4b0eb27859e1fa9b9831043907ae98)
[Kocsen](mailto:kocsenc@gmail.com) | crontab: add page | 2016-02-16T22:55:23 | [50ac0871403b](https://github.com/tldr-pages/tldr/commit/50ac0871403b958deef9ff5a6c856c57eef05897)

