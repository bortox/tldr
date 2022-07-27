---
author: ['Iksas', 'CleanMachine1']
date: 1650625609
title: "vcgencmd, TLDR Pages"
description: "vcgencmd, Print system information for a Raspberry Pi."
categories: "linux"
---
> More information: <https://www.raspberrypi.org/documentation/computers/os.html#vcgencmd>.

- List all available commands:

```bash
vcgencmd commands
```

- Print the current CPU temperature:

```bash
vcgencmd measure_temp
```

- Print the current voltage:

```bash
vcgencmd measure_volts
```

- Print the throttled state of the system as a bit pattern:

```bash
vcgencmd get_throttled
```

- Print the bootloader config (only available on Raspberry Pi 4 models):

```bash
vcgencmd bootloader_config
```

- Display Help:

```bash
vcgencmd --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Iksas](mailto:Iksas@users.noreply.github.com) | vcgencmd: update more information link (#8038) | 2022-04-22T13:06:49 | [5515e8daac69](https://github.com/tldr-pages/tldr/commit/5515e8daac69236a013e1e9111ed5f4ceef5ee22)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | vcgencmd: add page (#6309) | 2021-08-15T18:19:26 | [2bef4512ef65](https://github.com/tldr-pages/tldr/commit/2bef4512ef659ecc52c9c679848c0d71bdb7eceb)

