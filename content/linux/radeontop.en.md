---
author: ['Starbeamrainbowlabs', 'Seth Falco', 'Quentin']
date: 1656325392
title: "radeontop"
description: "radeontop, Show utilization of AMD GPUs."
categories: "linux"
---
> May require root privileges depending on your system.

> More information: <https://github.com/clbr/radeontop>.

- Show the utilization of the default AMD GPU:

```bash
radeontop
```

- Enable colored output:

```bash
radeontop --color
```

- Select a specific GPU (the bus number is the first number in the output of `lspci`):

```bash
radeontop --bus bus_number
```

- Specify the display refresh rate (higher means more GPU overhead):

```bash
radeontop --ticks samples_per_second
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Quentin](mailto:quentin.bettoum@mailo.com) | radeontop: update page (#6156) | 2021-07-18T12:41:38 | [6bc3ecf34a65](https://github.com/tldr-pages/tldr/commit/6bc3ecf34a658a3071c152c891417ce4aa64cb72)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | radeontop: add page (#3180) | 2019-07-08T04:46:12 | [2f8f860bb230](https://github.com/tldr-pages/tldr/commit/2f8f860bb230959010c7bc0ba21d31bfd2750d4e)

