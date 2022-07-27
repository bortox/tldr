---
author: ['Stig124', 'Max Xu', 'Agniva De Sarker']
date: 1625841955
title: "dmidecode, TLDR Pages"
description: "dmidecode, Display the DMI (alternatively known as SMBIOS) table contents in a human-readable format."
categories: "linux"
---
> Requires root privileges.

> More information: <https://manned.org/dmidecode>.

- Show all DMI table contents:

```bash
sudo dmidecode
```

- Show the BIOS version:

```bash
sudo dmidecode -s bios-version
```

- Show the system's serial number:

```bash
sudo dmidecode -s system-serial-number
```

- Show BIOS information:

```bash
sudo dmidecode -t bios
```

- Show CPU information:

```bash
sudo dmidecode -t processor
```

- Show memory information:

```bash
sudo dmidecode -t memory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | dmidecode: add cpu and memory information (#1990) | 2018-02-16T04:45:53 | [22d3ce22ab94](https://github.com/tldr-pages/tldr/commit/22d3ce22ab94027c70d25dabb430d0cc7368d439)
[Max Xu](mailto:xuhuan@live.cn) | Update dmidecode.md | 2018-01-02T09:53:54 | [7eb98c0a3f75](https://github.com/tldr-pages/tldr/commit/7eb98c0a3f753ce3f9e208960000c7cb8b084f31)
[Max Xu](mailto:xuhuan@live.cn) | Update dmidecode.md | 2018-01-01T13:10:21 | [dce4bf571ca2](https://github.com/tldr-pages/tldr/commit/dce4bf571ca284aecf33364d1727d3751968ad61)
[Max Xu](mailto:xuhuan@live.cn) | dmidecode.md: add page | 2018-01-01T09:59:03 | [a81a6fab3350](https://github.com/tldr-pages/tldr/commit/a81a6fab3350410b8548c455025821f82cccf125)

