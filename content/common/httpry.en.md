---
author: ['Argishti Rostamian']
date: 1602001725
title: "httpry, TLDR Pages"
description: "httpry, A lightweight packet sniffer for displaying and logging HTTP traffic."
categories: "common"
---
> It can be run in real-time displaying the traffic as it is parsed, or as a daemon process that logs to an output file.

> More information: <http://dumpsterventures.com/jason/httpry/>.

- Save output to a file:

```bash
httpry -o path/to/file.log
```

- Listen on a specific interface and save output to a binary pcap format file:

```bash
httpry eth0 -b path/to/file.pcap
```

- Filter output by a comma-separated list of HTTP verbs:

```bash
httpry -m get|post|put|head|options|delete|trace|connect|patch
```

- Read from an input capture file and filter by IP:

```bash
httpry -r path/to/file.log 'host 192.168.5.25'
```

- Run as daemon process:

```bash
httpry -d -o path/to/file.log
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Argishti Rostamian](mailto:1332785+WhileLoop@users.noreply.github.com) | httpry: add page (#4491) * httpry: add page * use token syntax | 2020-10-06T18:28:45 | [353e65521e0a](https://github.com/tldr-pages/tldr/commit/353e65521e0aa82fc606ef9fb9df7d83ad296dcb)

