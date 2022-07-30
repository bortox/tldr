---
author: ['bl-ue', 'Emily Grace Seville']
date: 1644837703
title: "SafeEjectGPU"
description: "SafeEjectGPU, Eject a GPU safely."
categories: "osx"
---
> More information: <https://www.unix.com/man-page/mojave/8/safeejectgpu>.

- Eject all GPUs:

```bash
SafeEjectGPU Eject
```

- List all GPUs attached:

```bash
SafeEjectGPU gpus
```

- List apps using a GPU:

```bash
SafeEjectGPU gpuid GPU_ID apps
```

- Get the status of a GPU:

```bash
SafeEjectGPU gpuid GPU_ID status
```

- Eject a GPU:

```bash
SafeEjectGPU gpuid GPU_ID Eject
```

- Launch an app on a GPU:

```bash
SafeEjectGPU gpuid GPU_ID LaunchOnGPU path/to/App.app
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | SafeEjectGPU: rename safeejectgpu (#5383) | 2021-03-08T11:38:46 | [9668011010b8](https://github.com/tldr-pages/tldr/commit/9668011010b863b072204ad5c62546867c8ff1ba)

