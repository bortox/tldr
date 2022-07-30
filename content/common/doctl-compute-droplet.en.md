---
author: ['258204']
date: 1639857171
title: "doctl compute droplet"
description: "doctl compute droplet, List, create, and delete virtual machines which are called droplets."
categories: "common"
---
> More information: <https://docs.digitalocean.com/reference/doctl/reference/compute/droplet/>.

- Create a droplet:

```bash
doctl compute droplet create --region region --image os_image --size vps_type droplet_name
```

- Delete a droplet:

```bash
doctl compute droplet delete droplet_id|droplet_name
```

- List droplets:

```bash
doctl compute droplet list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[258204](mailto:71364336+258204@users.noreply.github.com) | doctl-compute-droplet: add page (#7524) | 2021-12-18T20:52:51 | [0dd975ec3ac3](https://github.com/tldr-pages/tldr/commit/0dd975ec3ac37dae572142c403a292ede2a76e0e)

