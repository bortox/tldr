---
author: ['Reinhart Previano Koentjoro']
date: 1635013738
title: "warp-diag"
description: "warp-diag, Diagnostic and feedback tool for Cloudflare's WARP service."
categories: "common"
---
> See also: `warp-cli`.

> More information: <https://developers.cloudflare.com/warp-client/>.

- Generate a zip file with information about the system configuration and the WARP connection:

```bash
warp-diag
```

- Generate a zip file with debug information including a timestamp to the output filename:

```bash
warp-diag --add-ts
```

- Save the output file under a specific directory:

```bash
warp-diag --output path/to/directory
```

- Submit a new feedback to Cloudflare's WARP interactively:

```bash
warp-diag feedback
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | warp-cli, warp-diag: add page (#7087) | 2021-10-23T20:28:58 | [ae019ca6fe9c](https://github.com/tldr-pages/tldr/commit/ae019ca6fe9c9b61083f83dfb1fae9b144c35652)

