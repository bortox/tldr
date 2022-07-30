---
author: ['thiswind', 'Emily Grace Seville']
date: 1644837703
title: "ping"
description: "ping, Send ICMP ECHO_REQUEST packets to network hosts."
categories: "osx"
---
> More information: <https://ss64.com/osx/ping.html>.

- Ping the specified host:

```bash
ping "hostname"
```

- Ping a host a specific number of times:

```bash
ping -c count "host"
```

- Ping `host`, specifying the interval in `seconds` between requests (default is 1 second):

```bash
ping -i seconds "host"
```

- Ping `host` without trying to lookup symbolic names for addresses:

```bash
ping -n "host"
```

- Ping `host` and ring the bell when a packet is received (if your terminal supports it):

```bash
ping -a "host"
```

- Ping `host` and prints the time a packet was received (this option is an Apple addition):

```bash
ping --apple-time "host"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[thiswind](mailto:thiswind@gmail.com) | /osx/ping: add page | 2019-02-11T18:11:44 | [35949d984503](https://github.com/tldr-pages/tldr/commit/35949d98450303cdbfcb1a87c9bc5e876121dea1)

