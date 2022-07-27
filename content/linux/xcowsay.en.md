---
author: ['Mark Fischer, Jr']
date: 1634442897
title: "xcowsay, TLDR Pages"
description: "xcowsay, Display a cute cow and message on your Linux desktop."
categories: "linux"
---
> The cow is displayed for either a fixed amount of time, or an amount of time calculated from the size of the text. Click on the cow to dismiss it immediately.

> More information: <https://www.doof.me.uk/xcowsay/>.

- Display a cow saying "hello, world":

```bash
xcowsay "hello, world"
```

- Display a cow with output from another command:

```bash
ls | xcowsay
```

- Display a cow at the specified X and Y coordinates:

```bash
xcowsay --at=X,Y
```

- Display a different sized cow:

```bash
xcowsay --cow-size=small|med|large
```

- Display a thought bubble instead of a speech bubble:

```bash
xcowsay --think
```

- Display a different image instead of the default cow:

```bash
xcowsay --image=path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mark Fischer, Jr](mailto:flyingfisch@toppagedesign.com) | xcowsay: add page (#6974) | 2021-10-17T05:54:57 | [0f57987da067](https://github.com/tldr-pages/tldr/commit/0f57987da0677e71a28f64e29c2e1614eb71d314)

