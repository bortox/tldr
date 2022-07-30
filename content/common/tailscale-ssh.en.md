---
author: ['Muhammad Falak R Wani']
date: 1656549559
title: "tailscale ssh"
description: "tailscale ssh, SSH to a Tailscale machine (Linux Only)."
categories: "common"
---
> More information: <https://tailscale.com/kb/1193/tailscale-ssh>.

- Advertise/Disable SSH on the host:

```bash
sudo tailscale up --ssh=true|false
```

- SSH to a specific host which has Tailscale-SSH enabled:

```bash
tailscale ssh username@host
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | tailscale-ssh: add page (#8151) * tailscale-ssh: add page * tailscale-ssh: cosmetic fixes Co-authored-by: Emily Grace Seville [...] | 2022-06-30T02:39:19 | [371ad36a8897](https://github.com/tldr-pages/tldr/commit/371ad36a88978dd7959c95b3f98bca2b9d92db66)

