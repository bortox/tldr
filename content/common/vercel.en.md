---
author: ['Felix Swinkels', 'bl-ue']
date: 1616025476
title: "vercel"
description: "vercel, Deploy and manage your Vercel deployments."
categories: "common"
---
> More information: <https://vercel.com/docs/cli>.

- Deploy the current directory:

```bash
vercel
```

- Deploy the current directory to production:

```bash
vercel --prod
```

- Deploy a directory:

```bash
vercel path/to/project
```

- Initialize an example project:

```bash
vercel init
```

- Deploy with Environment Variables:

```bash
vercel --env ENV=var
```

- Build with Environment Variables:

```bash
vercel --build-env ENV=var
```

- Set default regions to enable the deployment on:

```bash
vercel --regions region_id
```

- Remove a deployment:

```bash
vercel remove project_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | vercel: fix typo (#5469) | 2021-03-18T00:57:56 | [7165d0e3472b](https://github.com/tldr-pages/tldr/commit/7165d0e3472bbe2fc1ac0752619f6b16dc6d92dd)
[Felix Swinkels](mailto:tgifelix@icloud.com) | vercel: add page (#5278) remove now.md page replaced by vercel | 2021-02-19T11:11:57 | [70a76e528037](https://github.com/tldr-pages/tldr/commit/70a76e52803783c2aae6afd985f0fdb27b7d4a05)

