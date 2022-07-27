---
author: ['Dan Kim', 'Juri', 'Waldir Pimenta']
date: 1634444636
title: "pssh, TLDR Pages"
description: "pssh, Parallel SSH program."
categories: "common"
---
> More information: <https://manned.org/pssh>.

- Run a command on two hosts, and print its output on each server inline:

```bash
pssh -i -H "host1 host2" hostname -i
```

- Run a command and save the output to separate files:

```bash
pssh -H host1 -H host2 -o path/to/output_dir hostname -i
```

- Run a command on multiple hosts, specified in a new-line separated file:

```bash
pssh -i -h path/to/hosts_file hostname -i
```

- Run a command as root (this asks for the root password):

```bash
pssh -i -h path/to/hosts_file -A -l root_username hostname -i
```

- Run a command with extra SSH arguments:

```bash
pssh -i -h path/to/hosts_file -x "-O VisualHostKey=yes" hostname -i
```

- Run a command limiting the number of parallel connections to 10:

```bash
pssh -i -h path/to/hosts_file -p 10 'cd dir; ./script.sh; exit'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | meshlabserver, nkf, obs, pax, pdfimages, pinky, pssh, s, sd, sendmail, sftp: add link (#6971) | 2021-10-17T06:23:56 | [977d4212d52c](https://github.com/tldr-pages/tldr/commit/977d4212d52c031de053f549d819b8b0e18ce184)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | pssh: improve page (#1466) | 2017-09-08T06:13:59 | [d61bfa85c6ae](https://github.com/tldr-pages/tldr/commit/d61bfa85c6aef83edef8909bd2880a0453ae8eb4)
[Dan Kim](mailto:deekim@users.noreply.github.com) | pssh: add page (#1422) | 2017-07-11T20:02:25 | [bf8cdbee451d](https://github.com/tldr-pages/tldr/commit/bf8cdbee451d7cc1650a7d0a1fa8e8200a459849)

