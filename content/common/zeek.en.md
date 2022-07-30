---
author: ['Seth Falco', 'marchersimon']
date: 1656325392
title: "zeek"
description: "zeek, Passive network traffic analyzer."
categories: "common"
---
> Any output and log files will be saved to the current working directory.

> More information: <https://docs.zeek.org/en/lts/quickstart.html#zeek-as-a-command-line-utility>.

- Analyze live traffic from a network interface:

```bash
sudo zeek --iface interface
```

- Analyze live traffic from a network interface and load custom scripts:

```bash
sudo zeek --iface interface script1 script2
```

- Analyze live traffic from a network interface, without loading any scripts:

```bash
sudo zeek --bare-mode --iface interface
```

- Analyze live traffic from a network interface, applying a `tcpdump` filter:

```bash
sudo zeek --filter path/to/filter --iface interface
```

- Analyze live traffic from a network interface using a watchdog timer:

```bash
sudo zeek --watchdog --iface interface
```

- Analyze traffic from a `pcap` file:

```bash
zeek --readfile path/to/file.trace
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | zeek: add page (#5453) | 2021-03-18T01:52:43 | [443a6d224bd7](https://github.com/tldr-pages/tldr/commit/443a6d224bd7c80a5219dfb86a68e741f7b2b6c5)

