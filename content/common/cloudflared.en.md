---
author: ['bl-ue', 'Faiz Azhar']
date: 1621541621
title: "cloudflared"
description: "cloudflared, Command-line tool to create a persistent connection to the Cloudflare network."
categories: "common"
---
> More information: <https://developers.cloudflare.com/argo-tunnel/>.

- Authenticate and associate the connection to a domain in the Cloudflare account:

```bash
cloudflared tunnel login
```

- Establish a tunnel to a host in Cloudflare from the local server:

```bash
cloudflared tunnel --hostname hostname localhost:port_number
```

- Establish a tunnel to a host in Cloudflare from the local server, without verifying the local server's certificate:

```bash
cloudflared tunnel --hostname hostname localhost:port_number --no-tls-verify
```

- Save logs to a file:

```bash
cloudflared tunnel --hostname hostname http://localhost:port_number --loglevel panic|fatal|error|warn|info|debug --logfile path/to/file
```

- Install cloudflared as a system service:

```bash
cloudflared service install
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Faiz Azhar](mailto:gabanz@gmail.com) | cloudflared, wrangler: add page (#4534) | 2020-11-10T12:46:02 | [f346bc66e77d](https://github.com/tldr-pages/tldr/commit/f346bc66e77d04a0fd843a988c80932c4b91e379)

