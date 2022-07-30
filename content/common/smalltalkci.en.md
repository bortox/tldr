---
author: ['Christoph Thiede']
date: 1640860048
title: "smalltalkci"
description: "smalltalkci, Framework for testing Smalltalk projects with GitHub Actions, Travis CI, AppVeyor, GitLab CI, and others."
categories: "common"
---
> More information: <https://github.com/hpi-swa/smalltalkCI>.

- Run tests for a configuration file:

```bash
smalltalkci path/to/.smalltalk.ston
```

- Run tests for the `.smalltalk.ston` configuration in the current directory:

```bash
smalltalkci
```

- Debug tests in headful mode (show VM window):

```bash
smalltalkci --headful
```

- Download and prepare a well-known smalltalk image for the tests:

```bash
smalltalkci --smalltalk Squeak64-Trunk
```

- Specify a custom Smalltalk image and VM:

```bash
smalltalkci --image path/to/Smalltalk.image -- vm path/to/vm
```

- Clean up caches and delete builds:

```bash
smalltalkci --clean
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Christoph Thiede](mailto:38782922+LinqLover@users.noreply.github.com) | smalltalkci: add page (#7580) | 2021-12-30T11:27:28 | [fb6c77ecfc68](https://github.com/tldr-pages/tldr/commit/fb6c77ecfc688d8493f0525147d27e59eae85ddc)

