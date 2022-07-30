---
author: ['Morgan Howard', 'Emily Grace Seville']
date: 1644837703
title: "emond"
description: "emond, Event Monitor service that accepts events from various services, runs them through a simple rules engine, and takes action."
categories: "osx"
---
> The actions can run commands, send email, or SMS messages.

> More information: <https://www.manpagez.com/man/8/emond/>.

- Start the daemon:

```bash
emond
```

- Specify rules for emond to process by giving a path to a file or directory:

```bash
emond -r path/to/file_or_directory
```

- Use a specific configuration file:

```bash
emond -c path/to/config
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Morgan Howard](mailto:morganhoward@users.noreply.github.com) | osx/*: add page for macOS interal daemons (#6705) appsleepd auditd avbdevided bird bnepd cfprefsd cloudphotod coreaudiod distnoted [...] | 2021-10-12T05:13:54 | [bb83c2b70569](https://github.com/tldr-pages/tldr/commit/bb83c2b705696df0df9a1b1407baf4df0ebd2ffe)

