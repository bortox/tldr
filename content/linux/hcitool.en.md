---
author: ['Vangeepuram Sreekesari']
date: 1629079805
title: "hcitool, TLDR Pages"
description: "hcitool, Monitor, configure connections, and send special commands to Bluetooth devices."
categories: "linux"
---
> More information: <https://manned.org/hcitool>.

- Scan for Bluetooth devices:

```bash
hcitool scan
```

- Output the name of a device, returning its MAC address:

```bash
hcitool name bdaddr
```

- Fetch information about a remote Bluetooth device:

```bash
hcitool info bdaddr
```

- Check the link quality to a Bluetooth device:

```bash
hcitool lq bdaddr
```

- Modify the transmit power level:

```bash
hcitool tpl bdaddr 0|1
```

- Display the link policy:

```bash
hcitool lp
```

- Request authentication with a specific device:

```bash
hcitool auth bdaddr
```

- Display local devices:

```bash
hcitool dev
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Vangeepuram Sreekesari](mailto:58507604+sreekesari-vangeepuram@users.noreply.github.com) | hcitool: add page (#6311) | 2021-08-16T04:10:05 | [d27d2eff5a82](https://github.com/tldr-pages/tldr/commit/d27d2eff5a82706c1a8f4c95c6bae66e2be2a9a9)

