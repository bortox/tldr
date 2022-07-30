---
author: ['Bartłomiej Tota']
date: 1635806150
title: "rtl_sdr"
description: "rtl_sdr, Raw data recorder for RTL-SDR receivers."
categories: "common"
---
> Data is encoded using I/Q sampling (aka quadrature sampling).

> More information: <https://osmocom.org/projects/rtl-sdr/wiki/Rtl-sdr>.

- Save RAW data from a frequency (specified in Hz) to a file:

```bash
rtl_sdr -f 100000000 path/to/file
```

- Pipe data to another program:

```bash
rtl_sdr -f 100000000 - | aplay
```

- Read a specified number of samples:

```bash
rtl_sdr -f 100000000 -n 20 -
```

- Specify the sample rate in Hz (ranges 225001-300000 and 900001-3200000):

```bash
rtl_sdr -f 100000000 -s 2400000 -
```

- Specify the device by its index:

```bash
rtl_sdr -f 100000000 -d 0 -
```

- Specify the gain:

```bash
rtl_sdr -f 100000000 -g 20 -
```

- Specify the output block size:

```bash
rtl_sdr -f 100000000 -b 9999999 -
```

- Use synchronous output:

```bash
rtl_sdr -f 100000000 -S -
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Bartłomiej Tota](mailto:bartlomiej.tota@outlook.com) | rtl_sdr: add page (#7029) | 2021-11-01T23:35:50 | [e4a8b992d1d1](https://github.com/tldr-pages/tldr/commit/e4a8b992d1d139bc09d2134644a5ded37d9a6318)

