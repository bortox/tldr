---
author: ['Vishal Verma', 'Emily Grace Seville']
date: 1647882468
title: "ndctl"
description: "ndctl, Utility for managing Non-Volatile DIMMs."
categories: "linux"
---
> More information: <https://manned.org/ndctl>.

- Create an 'fsdax' mode namespace:

```bash
ndctl create-namespace --mode=fsdax
```

- Change the mode of a namespace to 'raw':

```bash
ndctl create-namespace --reconfigure=namespaceX.Y --mode=raw
```

- Check a sector mode namespace for consistency, and repair if needed:

```bash
ndctl check-namespace --repair namespaceX.Y
```

- List all namespaces, regions, and buses (including disabled ones):

```bash
ndctl list --namespaces --regions --buses --idle
```

- List a specific namespace and include lots of additional information:

```bash
ndctl list -vvv --namespace=namespaceX.Y
```

- Run a monitor to watch for SMART health events for NVDIMMs on the 'ACPI.NFIT' bus:

```bash
ndctl monitor --bus=ACPI.NFIT
```

- Remove a namespace (when applicable) or reset it to an initial state:

```bash
ndctl destroy-namespace --force namespaceX.Y
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Vishal Verma](mailto:stellarhopper@gmail.com) | ndctl: add page (#2380) | 2018-10-06T13:13:21 | [21751a2315c7](https://github.com/tldr-pages/tldr/commit/21751a2315c78938acc48219b1ac53aad09c56a6)

