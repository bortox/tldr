---
author: ['Muhammad Falak R Wani']
date: 1646699611
title: "tailscale file"
description: "tailscale file, Send files across connected devices on a Tailscale network."
categories: "common"
---
> It currently does not support sending files to devices owned by other users even on the same Tailscale network.

> More information: <https://tailscale.com/kb/1106/taildrop/>.

- Send a file to a specific node:

```bash
sudo tailscale file cp path/to/file hostname|ip:
```

- Store files that were sent to the current node into a specific directory:

```bash
sudo tailscale file get path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | tailscale-file: add page (#7844) | 2022-03-08T01:33:31 | [c12a5c84333f](https://github.com/tldr-pages/tldr/commit/c12a5c84333fb51372ee3a2e466c1150817c6078)

