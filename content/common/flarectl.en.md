---
author: ['Josh Delsman']
date: 1661131883
title: "flarectl"
description: "flarectl, Official CLI for Cloudflare."
categories: "common"
---
> More information: <https://github.com/cloudflare/cloudflare-go/blob/master/cmd/flarectl/README.md>.

- Block a specific IP:

```bash
flarectl firewall rules create --zone="example.com" --value="8.8.8.8" --mode="block" --notes="Block bad actor"
```

- Add a DNS record:

```bash
flarectl dns create --zone="example.com" --name="app" --type="CNAME" --content="myapp.herokuapp.com" --proxy
```

- List all Cloudflare IPv4/IPv6 ranges:

```bash
flarectl ips --ip-type ipv4|ipv6|all
```

- Create many new Cloudflare zones automatically with names from `domains.txt`:

```bash
for domain in $(cat domains.txt); do flarectl zone info --zone=$domain; done
```

- List all firewall rules:

```bash
flarectl firewall rules list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Josh Delsman](mailto:screes.drain0p@icloud.com) | flarectl: add page (#8345) * flarectl: add page * Update pages/common/flarectl.md Co-authored-by: K.B.Dharun Krishna [...] | 2022-08-22T03:31:23 | [09b5bb8c045a](https://github.com/tldr-pages/tldr/commit/09b5bb8c045a451f43e5cd933099cbf246985d6c)

