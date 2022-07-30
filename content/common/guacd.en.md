---
author: ['nick lynch-jonely']
date: 1570125594
title: "guacd"
description: "guacd, Apache Guacamole proxy daemon."
categories: "common"
---
> Support loader for client plugins to interface between the Guacamole protocol and any arbitrary remote desktop protocol (e.g. RDP, VNC, Other).

> More information: <https://guacamole.apache.org/>.

- Bind to a specific port on localhost:

```bash
guacd -b 127.0.0.1 -l 4823
```

- Start in debug mode, keeping the process in the foreground:

```bash
guacd -f -L debug
```

- Start with TLS support:

```bash
guacd -C my-cert.crt -K my-key.pem
```

- Write the PID to a file:

```bash
guacd -p path/to/file.pid
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[nick lynch-jonely](mailto:nicholas.lynch-jonely@tektronix.com) | guacd: add page (#3296) * guacd: add page * Update pages/common/guacd.md Good feedback! Co-Authored-By: Starbeamrainbowlabs [...] | 2019-10-03T19:59:54 | [c2bde54e3322](https://github.com/tldr-pages/tldr/commit/c2bde54e332296be9c29f075b5c1015a48e06728)

