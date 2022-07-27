---
author: ['James Hibbard']
date: 1590589787
title: "nvidia-smi, TLDR Pages"
description: "nvidia-smi, Aid the management and monitoring of NVIDIA GPU devices."
categories: "common"
---
> More information: <https://developer.nvidia.com/nvidia-system-management-interface>.

- Display information on all available GPUs and processes using them:

```bash
nvidia-smi
```

- Display more detailed GPU information:

```bash
nvidia-smi --query
```

- Monitor overall GPU usage with 1-second update interval:

```bash
nvidia-smi dmon
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[James Hibbard](mailto:1940994+jameshibbard@users.noreply.github.com) | nvidia-smi: add page (#4065) | 2020-05-27T16:29:47 | [c19f05bf257d](https://github.com/tldr-pages/tldr/commit/c19f05bf257d42fc5bf7a94f7b767a86b7e78d0f)

